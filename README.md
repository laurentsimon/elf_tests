# elf_tests

[Analyzing headers](https://medium.com/@allypetitt/reverse-engineering-analyzing-headers-23dc84075cd)

## Debug symhols

```shell
$ nm --debug-syms

$ readelf -S | grep '.debug'

$ dwarfdump

#TODO: https://opensource.com/article/23/3/compiler-optimization-debugger-line-information
$ objdump -W
```

## Dynamic symbols

```shell
$ objdump -TC
```

## File header

```shell
$ readelf -e
```
