<p align="center">
<img src="https://github.com/tronicanet/ffmpeg/blob/master/imagenes/ffmpeg-logo-grande.png"/>
</p>
FFmpeg - multimedia framework

**Índice**   
1. [cambiar el contenedor de un video](#id1)
2. [cortar video](#id2)
3. [Eliminar el audio a un video](#id3)
4. [Cambiar la resolucion](#id3)

<a name="id1"></a>
## Cambiar el contenedor de un vieo

```
ffmpeg -i <input name> <output name>
```
<a name="id2"></a>
## Cortar video
<p align="center">
<img src="https://github.com/tronicanet/ffmpeg/blob/master/imagenes/cortar_video.png"/>
</p>

```
ffmpeg -i Video_input.mp4 -ss 00:06:12.000 -to 00:06:20.000 -c:v copy -c:a copy Video_salida.mp4

ffmpeg -ss [inicio_en_formato_hh:mm:ss] -t [duracion_segundos] -i [archivo_original] [archivo_salida]
```

## Eliminar el audio de un video<a name="id3"></a>

## cambiar la resolución de un video<a name="id4"></a>
```
ffmpeg -i input.mkv -aspect 16:9 -s 1920x1080 output.mkv
```

