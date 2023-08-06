GCC x86_64-elf cross compiler built for [BILL project](https://github.com/billyeatcookies/bill)

```dockerfile
FROM billywontexist/gcc-cross-x86_64-elf

RUN apt-get update 
RUN apt-get upgrade -y
RUN apt-get install -y grub-common

# do whatever
```
