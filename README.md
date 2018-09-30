## Repositorio de logos de las aplicaciones mas utilizadas en mis proyectos.

Los archivos SVG los he tomado de [svgporn][svgporn-link].

Para convertir los archivos SVG a formato PNG y [escalarlos][howtogeek-link] con [imageMagick][imagemagick-link] (fijando la altura), podeis usar el siguiente comando:

```bash
$ for file in *.svg; do convert "$file" -resize x36 ../png/"${file%.svg}.png"; done
```

Para añadir un borde blanco en la izquierda:

```bash
$ for file in *.svg; do convert "$file" -resize x36 -background white -splice 5x0 ../png-2/"${file%.svg}.png"; done
```

Preview:

![angular](https://mtzfactory.github.io/logos/png-2/angular.png)
![arduino](https://mtzfactory.github.io/logos/png-2/arduino.png)
![atom](https://mtzfactory.github.io/logos/png-2/atom.png)
![babel](https://mtzfactory.github.io/logos/png-2/babel.png)
![bootstrap](https://mtzfactory.github.io/logos/png-2/bootstrap.png)
![browserify](https://mtzfactory.github.io/logos/png-2/browserify.png)
![css](https://mtzfactory.github.io/logos/png-2/css-3.png)
![express](https://mtzfactory.github.io/logos/png-2/express.png)
![firebase](https://mtzfactory.github.io/logos/png-2/firebase.png)
![flask](https://mtzfactory.github.io/logos/png-2/flask.png)
![github](https://mtzfactory.github.io/logos/png-2/github.png)
![html-5](https://mtzfactory.github.io/logos/png-2/html-5.png)
![jasmine](https://mtzfactory.github.io/logos/png-2/jasmine.png)
![javascript](https://mtzfactory.github.io/logos/png-2/javascript.png)
![jquery](https://mtzfactory.github.io/logos/png-2/jquery.png)
![mongodb](https://mtzfactory.github.io/logos/png-2/mongodb.png)
![mysql](https://mtzfactory.github.io/logos/png-2/mysql.png)
![nodejs](https://mtzfactory.github.io/logos/png-2/nodejs.png)
![passport](https://mtzfactory.github.io/logos/png-2/passport.png)
![php](https://mtzfactory.github.io/logos/png-2/php.png)
![pug](https://mtzfactory.github.io/logos/png-2/pug.png)
![python](https://mtzfactory.github.io/logos/png-2/python.png)
![react](https://mtzfactory.github.io/logos/png-2/react.png)
![sass](https://mtzfactory.github.io/logos/png-2/sass.png)

[svgporn-link]: https://svgporn.com

[howtogeek-link]: https://www.howtogeek.com/109369/how-to-quickly-resize-convert-modify-images-from-the-linux-terminal/

[imagemagick-link]: http://www.imagemagick.org/script/index.php