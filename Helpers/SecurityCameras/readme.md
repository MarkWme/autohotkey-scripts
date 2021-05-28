# Security Cameras

These files are used in conjunction with the SecurityCameras.ahk script.

`mosaic-1920.vlm` is a VLC configuration file that sets up a feed with four feeds coming from a home security camera system.
`bg_1920x1080.jpg` is a blank jpg image that is used as the canvas for the four feeds

Copy both of the above files into the same folder as the VLC executable, then run

```dos
vlc --vlm-conf mosaic-1920.vlm
```
