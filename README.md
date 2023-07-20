# Image Prcessing in C++

The goal is to implement cool algorithms that process images.

Example output from dithering application.

![A dithered image. The image shows Sam from Death Stranding standing.](./deps/preview_dithering.png)

## Requirements

  - [cmake](https://cmake.org)
  - [vcpkg](https://vcpkg.io/en/index.html)

## Development

Setup the development environment with `cmake`.

```
cmake -S . -Bbuild -GNinja -DCMAKE_TOOLCHAIN_FILE=${VCPKG_ROOT}/scripts/buildsystems/vcpkg.cmake
```

`${VCPKG_ROOT}`: Follow their installation instruction and set this variable so that it points to where vcpkg is installed.

