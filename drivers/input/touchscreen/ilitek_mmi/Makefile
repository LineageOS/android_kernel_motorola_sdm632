#
# Makefile for the ipio touchscreen drivers.
#
# Each configuration option enables a list of files.

obj-$(CONFIG_TOUCHSCREEN_ILI9881H) += ilitek_mmi.o
ilitek_mmi-objs += platform.o userspace.o
ilitek_mmi-objs += core/config.o \
			      core/finger_report.o \
			      core/firmware.o \
			      core/flash.o \
			      core/i2c.o \
			      core/spi.o \
			      core/mp_test.o \
			      core/protocol.o \
			      core/parser.o \
			      core/gesture.o
