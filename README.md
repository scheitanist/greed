# greed
css flexbox grid

The <strong>greed</strong> is an alternative flexbox
grid. It's <b>light</b> & <b>smart</b>. 
You don't need to use classes on each grid element
(col) - use them on parent (row)!

# Layout

It's simple to use. You can forget naming 
each column in a row with a lot of classes, just 
add all needed classes to a row. 

Example:

Bootstrap:

`<div class="row">`<br/>
`<div class="col-lg-3 col-md-6 col-sm-12"></div>`  
`<div class="col-lg-3 col-md-6 col-sm-12"></div>`  
`<div class="col-lg-3 col-md-6 col-sm-12"></div>`  
`<div class="col-lg-3 col-md-6 col-sm-12"></div>`  
`</div>`

Greed:

`<div class="grid _4 _mobile">`<br/>
`<div class="grid__item"></div>`<br/>
`<div class="grid__item"></div>`<br/>
`<div class="grid__item"></div>`<br/>
`<div class="grid__item"></div>`<br/>
`</div>`

# Nesting

Nest inner grids the way you like

`<div class="grid _4">`<br/>
`<div class="grid__item">`<br/>
`<div class="grid _2">`<br/>
`<div class="grid__item"></div>`<br/>
`</div>`<br/>
`</div>`<br/>
`</div>`

or

`<div class="grid _4">`<br/>
`<div class="grid__item grid _2">`<br/>
`<div class="grid__item"></div>`<br/>
`</div>`<br/>
`</div>`

# Variables

All margins and paddings are set with css variable 
and is equal to 15px. Just change it in your css to
make paddings you need.