Bootstrappy Grid
====

Small, compact Bootstrap-inspired grid system written with Sass.

## How to do things
```html
<div class="container">
  <div class="row-md">
    <div class="col-4">.col-4</div>
    <div class="col-8">.col-8</div>
  </div>
</div>
```

![Grids!](http://i.imgur.com/XEdv9rQ.png)

### Columns
There are 12 columns by default. Their naming scheme is simply `.col-#{column_number}`. Perhaps not quite as flexible as defining the breakpoint inside the column class, but most people just use a single size class anyway.


### Rows

Changing the break point is as simple as changing the row class.

Always horizontal
`<div class="row-xs">`

Breaks at 750px
`<div class="row-sm">`

Breaks at 970px
`<div class="row-md">`

Breaks at 1170px
`<div class="row-lg">`

Note that if you set the class to `.row` it acts like a `.row-xs`.

### Containers
There are two types of containers: fixed and fluid.
`.container` is the fixed container, while `.container-fluid` is the fluid container. The difference is simply the fixed container's max-width is set to 1170px.

## But why?
Bootstrap is too heavy. Skeleton is weird. Pure isn't sassy enough. Blah blah blah. This is for a simple grid that's a bit more DRY than other grid systems. I did it because I wanted to. Use it if you want. I don't care. Use it however you want. I don't care.
