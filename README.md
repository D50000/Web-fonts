# Web-fonts
Use ```@font-face``` to configure the Web fonts by adding in css file.

# Download fonts
[https://fonts.google.com/](https://fonts.google.com/)  
**- WOFF / WOFF2** Web Open Font Format  
**- SVG / SVGZ** Scalable Vector Graphics (Font)  
**- EOT** Embedded Open Type  
**- OTF / TTF** OpenType Font and TrueType Font  

# CSS Syntax
```
@font-face {
  font-family: 'MyWebFont';
  src: url('webfont.eot'); /* IE9 Compat Modes */
  src: url('webfont.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
       url('webfont.woff2') format('woff2'), /* Super Modern Browsers */
       url('webfont.woff') format('woff'), /* Pretty Modern Browsers */
       url('webfont.ttf')  format('truetype'), /* Safari, Android, iOS */
       url('webfont.svg#svgFontName') format('svg'); /* Legacy iOS */
}
```

### Reference
[https://css-tricks.com/snippets/css/using-font-face/](https://css-tricks.com/snippets/css/using-font-face/)  
[https://codertw.com/%E5%89%8D%E7%AB%AF%E9%96%8B%E7%99%BC/182572/](https://codertw.com/%E5%89%8D%E7%AB%AF%E9%96%8B%E7%99%BC/182572/)  
[https://blog.gtwang.org/web-development/css-font-face/](https://blog.gtwang.org/web-development/css-font-face/)
