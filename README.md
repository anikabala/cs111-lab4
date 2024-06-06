# Hey! I'm Filing Here

In this lab, I successfully implemented a 1 MiB ext2 file system with 2 directories, 1 regular file, and 1 symbolic link. This mimcs an ext2 file system implementation.

## Building

```shell
make
```

I used the `make` command to make entire process and be able to run it from the command line. Using the makefile, this command compiles the binaries needed for it to run.

## Running

```shell
./ext2-create
```

This command calls the executable file that was made using the make command. Once called and run, it creates the cs111-base.img specified by the scope. 



## Cleaning up

```shell
make clean
```
This command cleans the directory of all binary/object and executable files, restoring it to what initially exists. 