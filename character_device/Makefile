obj-m += character_main.o

ccflags-y += -Wall

all:
	make -C /lib/modules/`uname -r`/build  M=$(PWD) modules

clean:
	make -C /lib/modules/`uname -r`/build M=$(PWD) clean
