obj-$(CONFIG_BACKPORT_IWLEGACY)	+= iwlegacy.o
iwlegacy-objs 		:= common.o
iwlegacy-$(CONFIG_BACKPORT_IWLEGACY_DEBUGFS) += debug.o

iwlegacy-objs += $(iwlegacy-m)

# 4965
obj-$(CONFIG_BACKPORT_IWL4965)	+= iwl4965.o
iwl4965-objs		:= 4965.o 4965-mac.o 4965-rs.o 4965-calib.o
iwl4965-$(CONFIG_BACKPORT_IWLEGACY_DEBUGFS) += 4965-debug.o

# 3945
obj-$(CONFIG_BACKPORT_IWL3945)	+= iwl3945.o
iwl3945-objs		:= 3945-mac.o 3945.o 3945-rs.o
iwl3945-$(CONFIG_BACKPORT_IWLEGACY_DEBUGFS) += 3945-debug.o

ccflags-y += -D__CHECK_ENDIAN__
