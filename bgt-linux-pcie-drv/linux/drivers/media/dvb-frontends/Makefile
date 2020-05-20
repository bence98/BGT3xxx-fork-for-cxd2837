#
# Makefile for the kernel DVB frontend device drivers.
#

EXTRA_CFLAGS += -Idrivers/media/dvb-core/
EXTRA_CFLAGS += -Idrivers/media/common/tuners/

cxd2820r-objs = cxd2820r_core.o cxd2820r_c.o cxd2820r_t.o cxd2820r_t2.o

obj-$(CONFIG_DVB_TDA18272) += tda18272.o
obj-$(CONFIG_DVB_CXD2820R) += cxd2820r.o
# obj-$(CONFIG_DVB_CXD2834) += cxd2834.o
obj-$(CONFIG_DVB_CXD2850) += cxd2850.o
obj-$(CONFIG_DVB_A8290) += a8290.o
obj-$(CONFIG_DVB_CXD2817) += cxd2817.o
obj-$(CONFIG_DVB_CXD2861) += cxd2861.o
obj-$(CONFIG_DVB_CXD2843) += cxd2843.o
