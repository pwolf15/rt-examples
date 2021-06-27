# VxWorks examples

``` shell
# host
source <SDK_DIR>/toolkit/wind_sdk_env.linux
cargo build hello
```

``` shell
# target
[vxWorks *]# ./hello.vxe
Launching process './hello.vxe' ...
Process './hello.vxe' (process Id = 0xffff80000080a730) launched.
Donald is eating.
Mark is eating.
Donald is done eating.
Mark is done eating.
Larry is eating.
Bruce is eating.
Larry is done eating.
Bruce is done eating.
John is eating.
John is done eating.
[vxWorks *]# 
```