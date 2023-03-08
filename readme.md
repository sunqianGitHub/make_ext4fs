[![GitHub](https://img.shields.io/github/license/rendiix/make_ext4fs.svg)](https://github.com/rendiix/make_ext4fs/blob/master/LICENSE)
[![HitCount](http://hits.dwyl.io/rendiix/make_ext4fs.svg)](https://github.com/sunqianGitHub/make_ext4fs)
[![GitHub release](https://img.shields.io/github/release/rendiix/make_ext4fs.svg)](https://github.com/sunqianGitHub/make_ext4fs/releases/)
[![Github all releases](https://img.shields.io/github/downloads/rendiix/make_ext4fs/total.svg)](https://github.com/sunqianGitHub/make_ext4fs/releases/)
[![GitHub forks](https://img.shields.io/github/forks/rendiix/make_ext4fs.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/sunqianGitHub/make_ext4fs/network/)
[![GitHub stars](https://img.shields.io/github/stars/rendiix/make_ext4fs.svg?style=social&label=Star&maxAge=2592000)](https://github.com/sunqianGitHub/make_ext4fs/stargazers/)
[![GitHub watchers](https://img.shields.io/github/watchers/rendiix/make_ext4fs.svg?style=social)](https://github.com/sunqianGitHub/make_ext4fs/watchers)
[![GitHub followers](https://img.shields.io/github/followers/rendiix.svg?style=social&label=Follow&maxAge=2592000)](https://github.com/sunqianGitHub?tab=followers)
[![GitHub contributors](https://img.shields.io/github/contributors/rendiix/make_ext4fs.svg)](https://github.com/sunqianGitHub/make_ext4fs/graphs/contributors/)

# make_ext4fs for android
# make_ext4fs img2simg simg2img simg2simg sefcontext_decompile

#### Join Discord or follow me on Twitter:

[![Discord](https://img.shields.io/discord/404576842419273729.svg?label=join%20discord&logo=discord)](https://discord.gg/5PmKhrc)
[![Twitter Follow](https://img.shields.io/twitter/follow/rendiix.svg?color=green&label=follow&logo=twitter&style=social)](https://twitter.com/rendiix)

#### How to build

>Make sure the NDK android is installed

```console
user@localhost:~/make_ext4fs$ build.sh --help
Usage ./build.sh <options>

Options:
  -t, --target   build single target i.e: <arm|aarch64|x86|x86_64>.
  -s, --static   compile static executable binary.
  -c, --compiler select compiler gcc or clang.
  -d, --debug    compile with debugable binary.
  -v, --verbose  verbose compilation.
  -h, --help     show this help message and exit.
  -q, --quiet    build with silent stdout
```
#### 

```console
user@localhost:~/make_ext4fs$ ./bin/make_ext4fs_android_arm64-v8a
Expected filename after options
make_ext4fs_android_arm64-v8a [ -l <len> ] [ -j <journal size> ] [ -b <block_size> ]
    [ -g <blocks per group> ] [ -i <inodes> ] [ -I <inode size> ]
    [ -L <label> ] [ -f ] [ -a <android mountpoint> ]
    [ -S file_contexts ] [ -C fs_config ] [ -T timestamp ]
    [ -z | -s ] [ -w ] [ -c ] [ -J ] [ -v ] [ -B <block_list_file> ]
    <filename> [<directory>]
