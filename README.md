# Convertir archivos en linux

# Con Convert

```
convert book.png book.jpg

convert -geometry 1600x1600 -density 200x200 -quality 100 file.pdf file.jpg

```

# GhostScript

```
gs -dNOPAUSE -dBATCH -sDEVICE=jpeg -r96 -sOutputFile='page-%00d.jpg' input.pdf
gs -dNOPAUSE -dBATCH -sDEVICE=pngalpha -r96 -sOutputFile='page-%00d.png' input.pdf
```

