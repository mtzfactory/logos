## Repositorio de logos de las aplicaciones mas utilizadas en mis proyectos.

Los archivos SVG los he tomado de [svgporn][svgporn-link].

Para convertir los archivos SVG a formato PNG y [escalarlos][howtogeek-link] (fijando la altura), podeis usar el siguiente comando:

```bash
$ for file in *.svg; do convert "$file" -resize x36 ../png/"${file%.svg}.png"; done
```

![angular](./png/angular.png)
![arduino](./png/arduino.png)
![atom](./png/atom.png)
![babel](./png/babel.png)
![bootstrap](./png/bootstrap.png)
![browserify](./png/browserify.png)
![css](./png/css-3.png)
![firebase](./png/firebase.png)
![github](./png/github.png)
![html-5](./png/html-5.png)
![jasmine](./png/jasmine.png)
![javascript](./png/javascript.png)
![jquery](./png/jquery.png)
![sass](./png/sass.png)

[svgporn-link]: https://svgporn.com

[howtogeek-link]: https://www.howtogeek.com/109369/how-to-quickly-resize-convert-modify-images-from-the-linux-terminal/