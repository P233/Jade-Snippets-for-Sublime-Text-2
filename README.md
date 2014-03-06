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
doctype html
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

    script(type="text/javascript", src="js/jquery-1.11.0.min.js")
    // if IE
      script(type="text/javascript", src="js/placeholder.js")
```

tplh5bp => 

```jade
doctype html
//- TODO: Don't forget to set lang !!
html(class="no-js")
  head
    //- TODO: Check if it's the good charset
    meta(charset='utf-8')
    meta(http-equiv='X-UA-Compatible', content='IE=edge')
    title
    meta(name='description', content='')
    meta(name='viewport', content='width=device-width, initial-scale=1')
    //- TODO : Place favicon.ico and apple-touch-icon.png in the root directory
    block css
      link(rel='stylesheet', href='css/normalize.css')
      link(rel='stylesheet', href='css/main.css')
    block top-script
      script(src='js/vendor/modernizr-2.7.1.min.js')
  body
    //-
      Add your site or application content here
    block main
      p Hello world! This is HTML5 Boilerplate.

    block bottom-script
      script(src='//ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js')
      script.
        window.jQuery || document.write('<script src="js/vendor/jquery-1.11.0.min.js"><\/script>')
      script(src='js/plugins.js')
      script(src='js/main.js')
      //- TODO : Google Analytics: change UA-XXXXX-X to be your site\'s ID.
      script.
        (function(b,o,i,l,e,r){b.GoogleAnalyticsObject=l;b[l]||(b[l]=
        function(){(b[l].q=b[l].q||[]).push(arguments)});b[l].l=+new Date;
        e=o.createElement(i);r=o.getElementsByTagName(i)[0];
        e.src='//www.google-analytics.com/analytics.js';
        r.parentNode.insertBefore(e,r)}(window,document,'script','ga'));
        ga('create','UA-XXXXX-X');ga('send','pageview');
```

### Other

ie     =>  ```// if lt IE 9```

## Contributors
[rs459](https://github.com/rs459)