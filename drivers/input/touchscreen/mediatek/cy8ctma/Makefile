include $(srctree)/drivers/misc/mediatek/Makefile.custom

# Linux driver folder
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/
ccflags-y += -I$(srctree)/arch/arm/mach-$(MTK_PLATFORM)/$(ARCH_MTK_PROJECT)/touchpanel/cy8ctma

obj-y	+=  cyttsp4_btn.o
obj-y	+=  cyttsp4_bus.o
obj-y	+=  cyttsp4_core.o
obj-y	+=  cyttsp4_device_access.o
obj-y	+=  cyttsp4_i2c.o
obj-y	+=  cyttsp4_loader.o
obj-y	+=  cyttsp4_mtb.o
obj-y	+=  cyttsp4_mt_common.o
obj-y	+=  mtk_ttsp.o
