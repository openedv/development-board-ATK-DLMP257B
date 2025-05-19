1、将多个1G的文件组合在一起生成交叉编译器

```c#
cat toolchain-part-* > atk-image-openstlinux-weston-stm32mp2.rootfs-x86_64-toolchain-5.0.3-snapshot-20250115-v1.0.sh
```

2、确保文件合并完成

```c#
sync
```


3、检查交叉编译器文件完整

```c#
ls -lh atk-image-openstlinux-weston-stm32mp2.rootfs-x86_64-toolchain-5.0.3-snapshot-20250115-v1.0.sh
```
