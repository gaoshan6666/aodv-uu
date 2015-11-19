obj-m := kaodv.o
kaodv-objs := kaodv-mod.o kaodv-debug.o kaodv-netlink.o kaodv-queue.o kaodv-ipenc.o kaodv-expl.o 


KDIR :=/home/wu/Desktop/edison/kernel/linux-edison-standard-build

PWD := $(shell pwd)

EXTRA_CFLAGS += 


default:
	$(MAKE)	-C $(KDIR) SUBDIRS=$(PWD) modules 


clean:
	rm -rf *.o *~
	rm *.ko

