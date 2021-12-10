# slock-foreground-image-patch
This patch adds foreground image to [slock](http://tools.suckless.org/slock/).

# configuration options
1. *imgpath - is path to image to display, image must be xpm file
2. imgwidth - width of the image
3. imgheight - height of the image
4. imgoffsetx - image offset from left side
5. imgoffsety - image offset from top side
6. showimgonlyatstart - if set to 1 image will be shown only at the start (before tipying), if set to 0 image will be always shown

# installation
Download [slock](http://tools.suckless.org/slock/) and slock-foreground-image.diff.
Copy slock-foreground-image.diff to the same folder where you have slock source code.
```bash
patch -p1 < slock-foreground-image-20211210.diff
```
