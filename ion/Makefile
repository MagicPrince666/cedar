obj-$(CONFIG_VIDEO_SUNXI_CEDAR_ION) +=	ion.o ion-ioctl.o ion_heap.o \
			ion_page_pool.o ion_system_heap.o \
			ion_carveout_heap.o ion_chunk_heap.o ion_cma_heap.o
ifdef CONFIG_COMPAT
obj-$(CONFIG_VIDEO_SUNXI_CEDAR_ION) += compat_ion.o
endif
obj-$(CONFIG_VIDEO_SUNXI_CEDAR_ION) += sunxi/
obj-$(CONFIG_VIDEO_SUNXI_CEDAR_ION) += ion_of.o