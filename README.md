durian
======

My Linux Kernel Module Study.

```c
printk("Kernel, to me, is like a durian.\n");
printk("Smells nasty, but tastes gorgeous.\n");
printk("Hope we all enjoy it.\n");
```

Try for yourself
```bash
make
insmod durianmod.ko
dmesg
rmmod durianmod.ko
```