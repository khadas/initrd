# Initial ramdisk for Khadas VIM

### Build steps
Fetch the source tree:
```sh
$ git clone https://github.com/khadas/initrd
```

Run `make`:
```sh
$ cd initrd
$ make
```
Generated file: ../image/initrd.img

### Credit
The initial version was based on:

* ubuntu-base-16.04.1-base-arm64
* [Linux-3.14.29](https://github.com/khadas/linux)
* Ubuntu initramfs-tools
