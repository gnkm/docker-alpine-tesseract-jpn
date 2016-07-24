# Dockerfile for tesseract
## Description

dockerfile for building container includes

- tesseract-ocr
- tessdata for english
- tessdata for japanese
- tessdata for hocr

## Example

basic usage

```
$ docker run --rm -v $HOME/docker-vol:/docker-vol -w /docker-vol gnkm/alpine-tesseract-jpn tesseract image-file output-file -l jpn
```
