#
# Makefile for MMC/SD card drivers
#

obj-$(CONFIG_MMC_BLOCK)		+= mmc_block.o
mmc_block-objs			:= block.o queue.o

ifeq ($(CONFIG_MACH_M2_KDI),y)
mmc_block-objs			+= cprmdrv_samsung.o
endif

obj-$(CONFIG_MMC_TEST)		+= mmc_test.o

obj-$(CONFIG_SDIO_UART)		+= sdio_uart.o

obj-$(CONFIG_MMC_BLOCK_TEST)		+= mmc_block_test.o
