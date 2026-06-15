# SPDX-License-Identifier: GPL-2.0

LINUXINCLUDE := -I$(src)/include -I$(src)/include/uapi $(LINUXINCLUDE)
subdir-ccflags-y := -include $(src)/include/hamradio_compat.h

obj-m += net/ax25/
obj-m += net/netrom/
obj-m += net/rose/
obj-m += drivers/net/hamradio/

obj-m += net/atm/
obj-m += drivers/atm/

obj-m += drivers/isdn/capi/
obj-m += drivers/isdn/mISDN/
obj-m += drivers/isdn/hardware/
obj-m += net/bluetooth/cmtp/

obj-m += net/appletalk/
