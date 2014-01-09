# Coding standards

## HTML
Pravidlá pre HTML

**HTML5 Doctype**
`<!DOCTYPE html>`

**Title**
Umiestnovať hneď za `<head>`

**Character Encoding**
`<meta charset="utf-8">`

**Link to CSS**
`<link rel="stylesheet" href="filename.css">`

**Link to LESS**
`<link rel="stylesheet/less" type="text/css" href="filename.less">`

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
### Obecné pravidlá

* V názvoch tried a ID používať pomlčky .class-name, .#id-name
* Jedna CSS vlastnosť = jeden riadok
* Používať dvojité úvodzovky
* Za každou hodnotou CSS vlastností vkladať bodkočiarku `CSS vlastnosť: hodnota;`
* Za názvom triedy (pred zloženou zátvorkou) vložiť medzeru `.class-name {`
* V deklarácii CSS vlastnosti za dvojbodkou vložiť medzeru `margin: 10px;`
* Pri nulových hodnotách CSS vlastnosti neuvádzať jednotku `margin: 0;`
* Pri deklarácii farieb v HEX formáte používať malé písmená

```css
.class-name {
 margin: 0;
 color: #000;
 padding: 5px 0;
}
```

### Komentáre
Slúžia nie len vám, ale aj ostatným v týme.

* Deľte kód do sekcií oddelených komentárom
* Komentár umiestnite vždy na začiatok sekcie


**Každý CSS dokument obsahuje názov a popis toho čo obsahuje.**
```css
/*
 *
 * Meno css/less súboru + popis
 *
 */
```

**Jenodriatkový css komentár**
```
// Označenie elementu
```

**Označenie sekcií**
```
// ToDo
```


### Názvy tried a ID
[Názvy tried - bem methodology] (http://coding.smashingmagazine.com/2012/04/16/a-new-front-end-methodology-bem/)

### CSS FIX
**IE7, IE8 fix:** `#idname { margin/*\**/: 5px\9; }`


## Scripts
Pravidlá pre Skripty
* Google Analytics kód musí byť umiestnený pred `</head>`
* [Modernizr](http://modernizr.com/download/#-fontface-backgroundsize-borderimage-borderradius-boxshadow-flexbox-hsla-multiplebgs-opacity-rgba-textshadow-cssanimations-csscolumns-generatedcontent-cssgradients-cssreflections-csstransforms-csstransforms3d-csstransitions-applicationcache-canvas-canvastext-draganddrop-hashchange-history-audio-video-indexeddb-input-inputtypes-localstorage-postmessage-sessionstorage-websockets-websqldatabase-webworkers-geolocation-inlinesvg-smil-svg-svgclippaths-touch-webgl-shiv-cssclasses-addtest-prefixed-teststyles-testprop-testallprops-hasevent-prefixes-domprefixes-load) kód musí byť umiestnený pred `</head>`
* jQuery z google cdn: `<script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>`

## Wordpress
Používam pluginy
* [Breadcrumb NavXT] (http://mtekk.us/code/breadcrumb-navxt/) - `<?php if(function_exists('bcn_display')) { bcn_display(); } ?>`
* [Contact Form 7] (http://contactform7.com) - `<?php echo do_shortcode('[contact-form-7 id="xxx" title="xxx"]'); ?>`
* [Google XML Sitemaps Generator] (http://www.arnebrachhold.de/projects/wordpress-plugins/google-xml-sitemaps-generator/)
* [Redirection] (http://urbangiraffe.com/plugins/redirection/) - 301 redirections
* [Regenerate Thumbnails] (http://www.viper007bond.com/wordpress-plugins/regenerate-thumbnails/)
* [SEO Ultimate] (http://www.seodesignsolutions.com/wordpress-seo/)
* [Broken Link Checker] (http://wordpress.org/plugins/broken-link-checker/)


## Coding tools
Nástroje, ktoré pri práci "každodenne" používam
 
* [Less.app](http://incident57.com/less/) - less kompilátor (vývoj skončil).
* [CodeKit](http://incident57.com/codekit/) - less kompilátor, live browser reloads, minify, optimizing images.
* [LittleIpsum](https://itunes.apple.com/cz/app/littleipsum/id405772121?mt=12) - generátor textov
* [Monosnap](https://itunes.apple.com/us/app/monosnap/id540348655) - jednoduchší nástroj na screenshot som nenašiel.
* [Dynamic Dummy Image Generator] (http://dummyimage.com) - generátor obrázkov.
* [Favicon Generator] (http://www.prodraw.net/favicon/index.php) - generátor favicon z png.
* [-prefix-free] (http://leaverou.github.com/prefixfree/)

**Browsers add-ons**
* [Auto Reload](https://addons.mozilla.org/en-US/firefox/addon/auto-reload/?src=api)

**Panic Coda 2**
Plugins
* [Emmet](http://docs.emmet.io)
* [My Coda 2 themes](https://github.com/ramino/Coda2themes)
