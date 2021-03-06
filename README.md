# Lunatic Rave 2 HD WMIX Recent Clear Retriever

This script reads text from screenshots of Lunatic Rave 2 WMIX HD's result screen. It retrieves information such as clear type and song level from the image. The information will be stored in **_recent.txt_** within the same directory. It will continue to do so in real time as more images are created.

- Version: **1**
- Licensed under: **GPLv3**

## Important Information
NORMAL CLEAR, HARD CLEAR, and FULL COMBO are supported. FAIL and EASY CLEAR are not supported.

## Requirements
- [WMIX HD Skin](https://onedrive.live.com/?authkey=%21AJDT%5FQWX9IJttnU&id=E92E2372413C5A12%21387&cid=E92E2372413C5A12)
- [OpenCV](https://pypi.org/project/opencv-python/)
- [PyTesseract](https://pypi.org/project/pytesseract/)
- [watchdog](https://pypi.org/project/watchdog/)

## Instructions
1) Place the script in the base directory of Lunatic Rave 2 HD.
2) Run **_recent.py_**.
3) Take screenshots of scores on WMIX HD's result screen.
4) Information will be stored in **_recent.txt_** located in the same directory.

## Example: 4 Screenshots recent.txt 
```
RECENT
st3 NC
sl10 HC
st0 HC
SP02 FC
```

![lr2](https://user-images.githubusercontent.com/45186205/137605041-8d472416-53cb-4466-b063-512059e29915.png)

