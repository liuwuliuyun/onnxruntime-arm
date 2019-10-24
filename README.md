# Onnxruntime for Raspberry Pi 4b
Onnxruntime builds for Raspberry Pi 4b, may also be used at other armv7l devices.

## Build Instructions
https://github.com/Microsoft/onnxruntime/blob/master/dockerfiles/Dockerfile.arm32v7

Noted Current master branch has issue (https://github.com/microsoft/onnxruntime/issues/1256) when cross-compiling, so make sure you use Dockerfile in this repo or you can directly download python wheel file.

## Install
pip3 install [package-name]
