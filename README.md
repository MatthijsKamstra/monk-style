# monkee-style 🐵

![](icon.png)

I ❤ [Bootstrap](https://getbootstrap.com/) I use it for most of my frontend project.

The most important reason for this is: it's been tested (a lot) and most common problems are fixed in Bootstrap.
Smarter people have collected the most effective way to build a framework.

If something doesn't work, I probably did something wrong! And that makes it much easier to figure out where the bugs are.

## 🤘

Sometimes I run into projects where I miss some of the stuff I am confortable with!

The primairy reason for the existance of the repe that I needed a grid. I wanted to copy paste something quick, but I noticed that I really don't know anything about flexbox. This is a great opportunity to find out.

I need a dropin minimal css framework just to do a quick fix in existing projects.

What I mostly need from a dropin css:

- layout (I have no idea why you would create a css framework without a layout, but there you have one of the reasons I needed this)
- positioning (flexbox)
- general utils for padding/margin (ala tailwind)

But why stop there ..

- buttons
- typography
- basic reset (normalize is a bit much)

and whatever I in the future add


## About the system

I'm writing down some ideas that should give you an idea what the library is based upon.

- `container` is `px` sized
- typography is `rem` based
- not interessted in IE (Internet Explorer)
- scss and css-vars (I need to think about this stuff)
- use css-vars to create an easy switch between dark mode?
- vars for colors (7/9 colors?)
- ...

**colors**

- default/primary
- secondary
- info
- success
- warning
- error
- light
- dark
- black
- white


**elements**

- base
- root
- color
- typography
- layout
- grid
- buttons
- hero

## basic rules?

height hero (perhaps others as well)

might concider `hero`/`panel` as names

- height-50 (medium)
- height-75 (large)
- height-100 (fullscreen)


screen widths

default mobile?


* -sm = small
* -md = medium
* -lg = large




## fix typography


- https://medium.com/codyhouse/create-your-design-system-part-1-typography-7c630d9092bd
- https://webdesign.tutsplus.com/tutorials/comprehensive-guide-when-to-use-em-vs-rem--cms-23984



## not included in library

I am not forcing you to use them, but you can add them and they will work

```html
<!-- Source® Sans Pro, Adobe's first open source typeface family, was designed by Paul D. Hunt. -->
<link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,700&display=swap" rel="stylesheet">
<!-- Ficons, A Simple, Open-Source, Drop-In Alternative for Font Awesome Icons  -->
<link href="https://cdn.jsdelivr.net/npm/ficons@1.1.52/dist/ficons/font.css" rel="stylesheet">
```

## Based on

the following examples:

- https://github.com/milligram/milligram
- https://github.com/ajusa/lit
- https://github.com/picturepan2/spectre
- https://github.com/getbase/base
- https://github.com/Chalarangelo/mini.css
- https://github.com/twbs/bootstrap


## Defaults I used in the lib

- Drop-In Alternative for Font Awesome Icons: [ficons](https://ficons.fiction.com/)
