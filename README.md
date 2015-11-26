##jquery.responsive-tables

A lightweight jQuery plugin  that allows table markup to become fully responsive. It provides a clean list  view via devices with small screens. It can work for multiple tables on a  single page, as well as with tables that contain various combinations of merged  cells. Best of all, it uses pure CSS for the rendering. 

###How to use

<ul>
    <li>include the <em>responsive-tables.css</em> in your page within the &lt;head&gt;&lt;/head&gt; tags</li>
    <li>Include the <em>jquery.responsive-tables.js</em> in your page after <a href="http://jquery.com/download/" target="_blank">jQuery</a></li>
    invoke the plugin within your custom scripts file, e.g. </li>
</ul>
```javascript
$(document).ready(function() {
    $.responsiveTables();    
});    
```
<ul>
    <li>Ensure that tables are marked up using the &lt;thead&gt;&lt;/thead&gt; and &lt;tbody&gt;&lt;/tbody&gt; tags</li>
    <li>Add the class 'respond' to the &lt;table&gt; tag of the chosen table(s), e.g.</li>
</ul>
```html
<table class="respond">
    <caption>Example</caption>
    <thead>
        ...
```

###customizations 

Within the responsive-tables.css style sheet, modifying the values of the ‘top’ and ‘left’ properties will change the perceived table heading padding at the “mobile” view. This will enable consitancy between the table heading and table data padding, e.g.
```css
table.respond td:before { 
		/* top/left values mimic padding */
		top: 8px;/* mimic padding top */
		left: 6px;/* mimic padding left */
```

###Author

Ryan Wells: [@ryanwellsdotcom][twitter]

###License

Licensed under [MIT][mit]. Enjoy.

[demo]: http://wagerfield.github.com/parallax/
[twitter]: http://twitter.com/wagerfield
[mit]: http://www.opensource.org/licenses/mit-license.php
[jquery]: http://jquery.com/
[zepto]: http://zeptojs.com/
[gulp]: http://gulpjs.com/
