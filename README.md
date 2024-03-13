# GStreamer template repository

```bash
GST_PLUGIN_PATH=gst-plugin gst-launch-1.0 -v filesrc location=../test.wav ! my_wav_filter ! audio/x-raw,format=S16LE,channels=1,rate=48000 ! autoaudiosink
```
