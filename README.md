# Dockerfile for tesseract
## Description

dockerfile for building container includes

- tesseract-ocr
- tessdata for english
- tessdata for japanese
- tessdata for hocr

## Example

```
$ docker run -it --name tesseract -v $HOME/docker-vol:/docker-vol -w /docker-vol gnkm/docker pull gnkm/alpine-tesseract-jpn /bin/ash
```
