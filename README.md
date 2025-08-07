# glibc 2.27

## 编译环境

- ubuntu-18.04

## 依赖

- gcc-8/g++-8
- texinfo

## 编译命令

```shell
mkdir build
../configure --prefix=/opt/dev/glibc-2.27
make -j$(proc)
sudo make install
```
