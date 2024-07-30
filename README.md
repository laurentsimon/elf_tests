# elf_tests

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
