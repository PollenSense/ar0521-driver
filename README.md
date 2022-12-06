# Linux MIPI Camera Driver for OnSemi AR0521 sensor

Based on https://github.com/sunny0917/ar0521

Back-porting for kernel version 5.10.92

The `ar0521-decompiled.dts` is the result of using `dtc` on PiOS to convert the buildroot-built `dtb` into a `dts` file.


helpful link for checking where methods exist in the kernel:

https://elixir.bootlin.com/linux/v5.10.92/source/include/media/v4l2-subdev.h#L413