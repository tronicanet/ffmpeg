# ffmpeg
FFmpeg - multimedia framework

**Índice**   
1. [cambiar el contenedor de un video](#id1)
2. [cortar video](#id2)
3. [Eliminar el audio a un video](#id3)

## Cambiar el contenedor de un vieo<a name="id1"></a>

```
ffmpeg -i <input name> <output name>
```

## Cortar video<a name="id2"></a>
<p align="center">
<img src="https://github.com/tronicanet/ffmpeg/blob/master/imagenes/cortar_video.png"/>
</p>

```
ffmpeg -i Video_input.mp4 -ss 00:06:12.000 -to 00:06:20.000 -c:v copy -c:a copy Video_salida.mp4
```

## Eliminar el audio de un video<a name="id3"></a>



