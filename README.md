# ffmpeg
FFmpeg - multimedia framework

* Cambiar el contenedor de un video

```
ffmpeg -i <input name> <output name>
```

* cortar video
```
ffmpeg -i Video_input.mp4 -ss 00:06:12.000 -to 00:06:20.000 -c:v copy -c:a copy Video_salida.mp4
```
