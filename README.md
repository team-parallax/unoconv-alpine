# unoconv-alpine

This Dockerfile builds an `node:alpine` image with unoconv installed.

## How to use

In case you do not want to modify the current image, you can use `unoconv-alpine` by running:

```console
docker pull teamparallax/unoconv-alpine
```

## Build your own unoconv-alpine

If your needs require further installations or modifications in the container, change the `Dockerfile` and build your image by running:

```console
docker build -t <YOUR_TAG> -f ./Dockerfile .
```
