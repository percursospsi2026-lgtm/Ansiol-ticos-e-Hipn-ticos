# Landing page do Atlas Sináptico

Abra `index.html` no navegador. A página contém os 11 slides da apresentação enviada, animações suaves e dois espaços para vídeos no final.

## Inserir vídeo do YouTube
Em cada bloco `<div class="video-shell">`, substitua o conteúdo interno por:

```html
<iframe src="https://www.youtube.com/embed/ID_DO_VIDEO" title="Vídeo do Atlas" allowfullscreen></iframe>
```

## Inserir vídeo MP4
Copie os arquivos para `assets/video1.mp4` e `assets/video2.mp4` e use:

```html
<video controls>
  <source src="assets/video1.mp4" type="video/mp4">
</video>
```


## Vídeo 1 já inserido
O arquivo `assets/video1.mp4` já está integrado ao primeiro espaço de vídeo. O segundo espaço permanece reservado até o envio do segundo arquivo.
