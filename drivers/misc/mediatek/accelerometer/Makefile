include $(srctree)/drivers/misc/mediatek/Makefile.custom

# In case the platform does NOT support this type of sensors

obj-y   +=  accel.o accel_factory.o

ifeq ($(CONFIG_MTK_MMA8452Q_AUTO),y)
obj-y   +=  mma8452q_auto/
endif

ifeq ($(CONFIG_MTK_KX023_AUTO),y)
obj-y   +=  kx023_auto/
endif

ifeq ($(CONFIG_MTK_LIS3DH_AUTO),y)
obj-y   +=  lis3dh_auto/
endif

