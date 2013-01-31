# Coding standards

## HTML
Pravidlá pre HTML

**HTML5 Doctype**
`<!DOCTYPE html>`

**Title**
Umiestnovať hneď za `<head>`

**Character Encoding**
`<meta charset="utf-8">`

**Pripraviť**
* pripraviť robots.txt
* pripraviť favicon a umiestniť do root adresára

**HTML komentár**
Umiestnovať na konci divu `</div><!--/.class-name-->`

**Fixing IE**
```
<!--[if IE 7 ]><![endif]-->
<!--[if IE 8 ]><![endif]-->
<!--[if IE 9 ]><![endif]-->
<!--[if lt IE 7 ]><![endif]-->
```

## CSS
Pravidlá pre CSS a LESS

**Link to CSS**
`<link rel="stylesheet" href="filename.css">`

**Link to LESS**
`<link rel="stylesheet/less" type="text/css" href="filename.less">`

* názvy tried a ID pre oddelenie používať pomlčky
* CSS vlastnosti na jeden riadok
* dvojité úvodzovky
* za názvom class vložiť medzeru `.class-name {`

**CSS komentár na označenie css/less dokumentu**

```
/*
 * Meno css/less súboru + popis
 */
```

**CSS komentár na označenie class v dokumente**
```
// Označenie elementu
```

IE7, IE8 fix: `#idname { margin/*\**/: 5px\9; }`

## Scripts
Pravidlá pre Skripty
* Google Analytics kód musí byť umiestnený pred `</head>`
* [Modernizr](http://modernizr.com/download/#-fontface-backgroundsize-borderimage-borderradius-boxshadow-flexbox-hsla-multiplebgs-opacity-rgba-textshadow-cssanimations-csscolumns-generatedcontent-cssgradients-cssreflections-csstransforms-csstransforms3d-csstransitions-applicationcache-canvas-canvastext-draganddrop-hashchange-history-audio-video-indexeddb-input-inputtypes-localstorage-postmessage-sessionstorage-websockets-websqldatabase-webworkers-geolocation-inlinesvg-smil-svg-svgclippaths-touch-webgl-shiv-cssclasses-addtest-prefixed-teststyles-testprop-testallprops-hasevent-prefixes-domprefixes-load) kód musí byť umiestnený pred `</head>`
* jQuery z google cdn: `<script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js"></script>`

## Coding tools
Nástroje, ktoré pri práci každodenne používam
 
* [Less.app](http://incident57.com/less/)

**Browsers add-ons**
* [Auto Reload](https://addons.mozilla.org/en-US/firefox/addon/auto-reload/?src=api)

**Panic Coda 2**
Plugins
* [Emmet](http://docs.emmet.io)
* [My Coda 2 themes](https://github.com/ramino/Coda2themes)