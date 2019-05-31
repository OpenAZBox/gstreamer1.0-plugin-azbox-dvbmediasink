# gstreamer1.0-plugin-azbox-dvbmediasink
Based on https://github.com/OpenPLi/gst-plugin-dvbmediasink

Some boxes need a max pcm rate off 48000.
For those boxes add --with-max-pcmrate-48K

Default for all AZBox:
```
DVBMEDIASINK_CONFIG = "--with-wma --with-wmv --with-pcm --with-dtsdownmix --with-azbox"
```
Default for azboxhd (Some images):
```
DVBMEDIASINK_CONFIG = "--with-wma --with-wmv --with-pcm --with-dtsdownmix --with-azboxhd"
```
