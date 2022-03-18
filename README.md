## msvc-bash-env

> Initialize a MSVC environment for your shell

### Install

Available as a [bpkg](http://www.bpkg.sh/)

```sh
bpkg install -g socketsupply/msvc-bash-env
```

### Usage

```sh
source "$(which msvc-bash-env)"
```

### Example

```sh
$ source "$(which msvc-bash-env)"
 info: Assuming x64 as platform
 info: Specify the platform as the first argument for this script to override
 info: Looking for 'vcvarsall.bat'
 info: clang++=/c/Program Files (x86)/Microsoft Visual Studio/2019/BuildTools/VC/Tools/Llvm/x64/bin/clang++
 info: Clang=/c/Program Files (x86)/Microsoft Visual Studio/2019/BuildTools/VC/Tools/Llvm/x64/bin/clang
```

### License

MIT
