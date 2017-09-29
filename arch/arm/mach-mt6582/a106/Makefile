
include $(srctree)/drivers/misc/mediatek/Makefile.custom

# Module project related part

ifeq ($(CONFIG_MTK_SENSOR_SUPPORT),y)
ifeq ($(CONFIG_MTK_TMD2772_AUTO),y)
obj-y	+=  alsps/tmd2772_auto/
endif

ifeq ($(CONFIG_MTK_KXCJK_1013_AUTO),y)
obj-y   +=  accelerometer/kxcjk_1013_auto/
endif

ifeq ($(CONFIG_MTK_LIS3DH_AUTO),y)
obj-y   +=  accelerometer/lis3dh_auto/
endif

ifeq ($(CONFIG_MTK_ST480_AUTO),y)
obj-y	+=  magnetometer/st480_auto/
endif

ifeq ($(CONFIG_MTK_MMC3516X_AUTO),y)
obj-y	+=  magnetometer/mmc3516x_auto/
endif


endif

ifneq ($(CONFIG_ARCH_MTK_PROJECT),)
ARCH_MTK_PROJECT := $(shell echo $(CONFIG_ARCH_MTK_PROJECT))
obj-y	+= core/
obj-y	+= dct/dct/
endif

obj-y   +=  lcm/
#obj-y	+=  hdmi/
obj-y	+=  camera/camera/
obj-y	+=  imgsensor/ov5648_mipi_raw_darling/
obj-y	+=  imgsensor/ov5648_mipi_raw_truly/
obj-y	+=  imgsensor/ov5648_mipi_raw_sunwin/
obj-y	+=  imgsensor/ov5648_mipi_raw_darling_zl/
obj-y	+=  imgsensor/hi258_mipi_yuv_cmk/
obj-y	+=  imgsensor/hi258_mipi_yuv_sw/
obj-y   +=  flashlight/constant_flashlight/
obj-y	+=  vibrator/
obj-y	+=  leds/
obj-y	+=  keypad/
obj-y	+=  sound/
obj-y	+=  accdet/
obj-y	+=  partition/

