include $(srctree)/drivers/misc/mediatek/Makefile.custom

# In case the platform does NOT support this type of sensors
obj-y   +=  alsps.o
obj-y   +=  alsps_factory.o
obj-y   +=  aal_control.o

ifeq ($(CONFIG_MTK_EPL2182),y)
obj-y	+=  EPL2182/
endif

ifeq ($(CONFIG_MTK_TMD2771_HW_AUTO),y)
obj-y	+=  tmd2771_HW_auto/
endif
