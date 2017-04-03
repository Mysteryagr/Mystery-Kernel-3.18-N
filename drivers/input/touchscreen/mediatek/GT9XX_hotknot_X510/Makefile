include $(srctree)/drivers/misc/mediatek/Makefile.custom

# Linux driver folder
#ccflags-y += -I$(srctree)/drivers/misc/mediatek/mach/$(MTK_PLATFORM)/$(ARCH_MTK_PROJECT)/touchpanel/GT9XX_hotknot_X510/
#ccflags-y += -I$(srctree)/arch/arm/mach-$(MTK_PLATFORM)/$(ARCH_MTK_PROJECT)/touchpanel/GT9XX_hotknot_X510/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/GT9XX_hotknot_X510/inc/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/$(MTK_PLATFORM)/include/

obj-y	+=  goodix_tool.o
obj-y	+=  gt9xx_driver.o
obj-y	+=  gt9xx_update.o

