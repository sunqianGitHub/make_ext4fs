# make_ext4fs for android
# make_ext4fs img2simg simg2img simg2simg sefcontext_decompile


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
