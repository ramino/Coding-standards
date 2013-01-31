# Coding standards

## HTML

**HTML5 Doctype**
`<!DOCTYPE html>`

**Title**
Umiestnovať hneď za `<head>`

**Character Encoding**
`<meta charset="utf-8">`

**Pripraviť**
* pripraviť robots.txt
* pripraviť favicon a umiestniť do root adresára

**Fixing IE**
```
<!--[if IE 7 ]><![endif]-->
<!--[if IE 8 ]><![endif]-->
<!--[if IE 9 ]><![endif]-->
<!--[if lt IE 7 ]><![endif]-->
```

## CSS

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

## Coding tools
* [Less.app](http://incident57.com/less/)

**Browsers add-ons
* [Auto Reload](https://addons.mozilla.org/en-US/firefox/addon/auto-reload/?src=api)

**Panic Coda 2**
Plugins
* [Emmet](http://docs.emmet.io)
* [My Coda 2 themes](https://github.com/ramino/Coda2themes)