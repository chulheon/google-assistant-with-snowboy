# Google Assistant Service
[https://developers.google.com/assistant/sdk/guides/service/python/](https://developers.google.com/assistant/sdk/guides/service/python/)

依文件流程安裝，確認可以正常執行

```
(assistant) pi@raspberrypi: googlesamples-assistant-pushtotalk \
  --project-id my-project-id \
  --device-model-id my-device-model-id \
```

# Snowboy Hotword Detection
[https://github.com/Kitt-AI/snowboy](https://github.com/Kitt-AI/snowboy)
[https://snowboy.kitt.ai/dashboard](https://snowboy.kitt.ai/dashboard)

依文件流程安裝，確認可以正常執行

```
(assistant) pi@raspberrypi:~/snowboy/examples/Python3 $ python demo.py \
  ../../resources/models/snowboy.umdl 
```

## macOS

```
(assistant) (master)⚡ % cd macOS
(assistant) (master)⚡ % python demo.py \
  --project-id my-project-id \
  --device-model-id my-device-model-id \
  --hotword-model resources/<snowboy.umdl | my_hotword.pmdl>
```

## Linux

```
(assistant) (master)⚡ cd linux
(assistant) (master)⚡ python demo.py \
  --project-id my-project-id \
  --device-model-id my-device-model-id \
  --hotword-model resources/<snowboy.umdl | my_hotword.pmdl>

```

## Raspberry Pi

```
(assistant) pi@raspberrypi:~ $ cd raspberrypi
(assistant) pi@raspberrypi:~/raspberrypi $ python demo.py \
  --project-id my-project-id \
  --device-model-id my-device-model-id \
  --hotword-model resources/<snowboy.umdl | my_hotword.pmdl>

```