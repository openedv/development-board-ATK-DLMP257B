1.Multiple 1G files are combined together to generate the cross-compiler

```c#
cat toolchain-part-* > atk-image-openstlinux-weston-stm32mp2.rootfs-x86_64-toolchain-5.0.3-snapshot-20250115-v1.0.sh
```

2.Make sure the files are merged

```c#
sync
```


3.Check that the cross-compiler file is complete

```c#
ls -lh atk-image-openstlinux-weston-stm32mp2.rootfs-x86_64-toolchain-5.0.3-snapshot-20250115-v1.0.sh
```
