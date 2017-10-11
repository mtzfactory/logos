## Repositorio de logos de las aplicaciones mas utilizadas en mis proyectos.

Los archivos SVG los he tomado de [svgporn][svgporn-link].

Para convertir los archivos SVG a formato PNG y [escalarlos][howtogeek-link] con [imageMagick][imagemagick-link] (fijando la altura), podeis usar el siguiente comando:

```bash
$ for file in ./svg/*.svg; do convert "$file" -resize x36 https://mtzfactory.github.io/logos/png/"${file%.svg}.png"; done
```

Preview:

![angular](https://mtzfactory.github.io/logos/png/angular.png)
![arduino](https://mtzfactory.github.io/logos/png/arduino.png)
![atom](https://mtzfactory.github.io/logos/png/atom.png)
![babel](https://mtzfactory.github.io/logos/png/babel.png)
![bootstrap](https://mtzfactory.github.io/logos/png/bootstrap.png)
![browserify](https://mtzfactory.github.io/logos/png/browserify.png)
![css](https://mtzfactory.github.io/logos/png/css-3.png)
![firebase](https://mtzfactory.github.io/logos/png/firebase.png)
![github](https://mtzfactory.github.io/logos/png/github.png)
![html-5](https://mtzfactory.github.io/logos/png/html-5.png)
![jasmine](https://mtzfactory.github.io/logos/png/jasmine.png)
![javascript](https://mtzfactory.github.io/logos/png/javascript.png)
![jquery](https://mtzfactory.github.io/logos/png/jquery.png)
![python](https://mtzfactory.github.io/logos/png/python.png)
![react](https://mtzfactory.github.io/logos/png/react.png)
![sass](https://mtzfactory.github.io/logos/png/sass.png)

[svgporn-link]: https://svgporn.com

[howtogeek-link]: https://www.howtogeek.com/109369/how-to-quickly-resize-convert-modify-images-from-the-linux-terminal/

[imagemagick-link]: http://www.imagemagick.org/script/index.php