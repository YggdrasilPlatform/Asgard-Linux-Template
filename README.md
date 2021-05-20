# Asgard Template for Linux

## Usage

### Environment setup
To build this project, the easiest way is to download and compile buildroot and use the meson cross-compilation.conf file and the cross compiler it provides.
Alternatively, it's also possible to use a generic `arm-linux-gnueabihf-gcc` / `arm-linux-gnueabihf-g++` compiler and write the cross config file manually for it.

```
$ meson build --cross-file=stm32mp1
```

### Compiling
```
$ meson compile -C build
```

