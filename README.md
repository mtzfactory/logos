for file in *.svg; do convert "$file" -resize x36 ../png/"${file%.svg}.png"; done

https://www.howtogeek.com/109369/how-to-quickly-resize-convert-modify-images-from-the-linux-terminal/