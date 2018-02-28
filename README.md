# arm-xc. ARM CrossCompile image

Image with tools for crosscompile for arm architectures (like Android)

## Build

```bash
$ docker build -t scarrascoh/arm-xc:1.23.0 .
```

## Run

```bash
$ docker run -ti --name arm-xc scarrascoh/arm-xc:1.23.0 bash
```

# About crosstool-ng

This docker images uses crosstool-ng as toolchains for generate binaries for cross-compiling. You can find more info about it at their site [crosstool-ng.org](http://crosstool-ng.org/)
