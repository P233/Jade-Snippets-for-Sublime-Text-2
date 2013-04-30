# [Jade Snippets for Sublime Text 2](https://github.com/P233/Jade-Snippets-for-Sublime-Text-2)

A collection of Jade snippets. All suggestions are welcome.

## Installation
Strongly recommend to install this repo through Package Control.

## Snippets List


### Attributes

id     =>  ```id=""```

cla    =>  ```class=""```

hre    =>  ```href=""```

src    =>  ```src=""```

typ    =>  ```type=""```

nam    =>  ```name=""```

rel    =>  ```rel=""```

con    =>  ```content=""```

val    =>  ```value=""```

tar    =>  ```target=""```

act    =>  ```action=""```

met    =>  ```method=""```

pla    =>  ```placeholder=""```

ari    =>  ```aria-*=""```

itemt  =>  ```itemtype="http://schema.org/*"```

items  =>  ```itemscope=""```

itemp  =>  ```itemprop```

rol    =>  ```role=""```

data   =>  ```data-*=""```


### Elements

a      =>  ```a(href="http://", target="_blank")```

img    =>  ```img(src="image/", alt="")```

scr    =>  ```script(type="text/javascript", src="")```

lin    =>  ```link(rel="stylesheet", type="text/css", href="")```


### Forms

form   =>  ```form(id="", method="", action="")```

inp    =>  ```input(type="text", placeholder="")```

but    =>  ```button(type="button", placeholder="")```

tex    =>  ```textarea(placeholder="")```

pli    =>  ```p > label(for="") + input(id="", type="")```


### Jade Specific

exte   =>  ```extend```

inc    =>  ```include```

mix    =>  ```mixin name(param1, param2)```

### Filters

st    =>  ```:stylus```

le    =>  ```:less```

md    =>  ```:markdown```

cd    =>  ```:cdata```

co    =>  ```:coffeescript```


### Templates

tem    =>  

```jade
!!!
html
  head(lang="en")
    title ${1:title name}
    meta(http-equiv="content-type", content="text/html; charset=UTF-8")
    meta(name="description", content="")
    meta(name="keywords", content="")
    meta(name="viewport", content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0;")
    // if lt IE 9
      script(type="text/javascript", src="js/html5shiv.js")
    link(rel="stylesheet", href="css/style.css", type="text/css")
  body
    header
      h1
    .container

    footer

    script(type="text/javascript", src="js/jquery-1.7.2.min.js")
    // if IE
      script(type="text/javascript", src="js/placeholder.js")
```

tplh5bp => 

```jade
!!!5
//- TODO: Don't forget to set lang !!
|<!--[if lt IE 7]>      <html class="no-js lt-ie9 lt-ie8 lt-ie7"> <![endif]-->
|<!--[if IE 7]>         <html class="no-js lt-ie9 lt-ie8"> <![endif]-->
|<!--[if IE 8]>         <html class="no-js lt-ie9"> <![endif]-->
|<!--[if gt IE 8]><!--> <html class="no-js"> <!--<![endif]-->
html
  head
    //- TODO: Check if it's the good charset
    meta(charset='utf-8')
    meta(http-equiv='X-UA-Compatible', content='IE=edge')
    title
    meta(name='description', content='')
    meta(name='viewport', content='width=device-width')
    //- TODO : Place favicon.ico and apple-touch-icon.png in the root directory
    block css
      link(rel='stylesheet', href='css/normalize.css')
      link(rel='stylesheet', href='css/main.css')
    block top-script    
      script(src='js/vendor/modernizr-2.6.2.min.js')
  body
    //-
      Add your site or application content here
    block main
      p Hello world! This is HTML5 Boilerplate.
    
    block bottom-script
      script(src='//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js')
      script
        window.jQuery || document.write('<script src="js/vendor/jquery-1.9.1.min.js"><\\/script>')
      script(src='js/plugins.js')
      script(src='js/main.js')
      //- TODO : Google Analytics: change UA-XXXXX-X to be your site\'s ID. 
      script
        var _gaq=[['_setAccount','UA-XXXXX-X'],['_trackPageview']];
        (function(d,t){var g=d.createElement(t),s=d.getElementsByTagName(t)[0];
        g.src='//google-analytics.com/ga.js';
        s.parentNode.insertBefore(g,s)}(document,'script'));
```

### Other

ie     =>  ```// if lt IE 9```

## Contributors
[rs459](https://github.com/rs459)