Fart是art平台下利用主动调用实现的脱壳方案。本项目修改自FART项目，在项目中搜索`fart`即可看到更改的地方

## 编译

1. 覆盖本项目到Android源码的相应目录

2. 执行`source build/envsetup.sh`

3. 执行`make update-api`

4. 执行`make systemimage` 

## 镜像

- [Nexus5 Android7.1](https://share.weiyun.com/LsNOcHJv) 密码：6ec5yz

## Dex修复

```
java -jar DexRepair.jar /path/to/dex /path/to/bin
```

## 感谢

- [FART](https://github.com/hanbinglengyue/FART)