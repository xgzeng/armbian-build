1. create file `userpatches/config-nanopi-r5s.conf`:

```sh
BOARD=nanopi-r5s
BRANCH=edge
RELEASE=bookworm
BUILD_MINIMAL=yes
BUILD_DESKTOP=no
KERNEL_CONFIGURE=no

#export HTTP_PROXY=http://127.0.0.1:1080
#export HTTPS_PROXY=http://127.0.0.1:1080
```

2. execute `./compile.sh nanopi-r5s`