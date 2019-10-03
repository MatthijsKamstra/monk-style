# monkee-style

![](icon.png)

I ❤ [Bootstrap](https://getbootstrap.com/) I use it for all the frontend project I do.

The most important reason for this is: it's been tested (a lot) and most common problems are fixed in Bootstrap.
Smarter people have collected the most effective way to build a framework.

If something doesn't work, I probably did something wrong! And that makes it much easier to figure out where the bugs are.


So when "someone" starts with a `I-am-a-frontend-developer-and-I-never-use-a-framework-bullshit.css`, I sometimes miss stuff that I need.

In this case I missed a grid. I wanted to copy paste something quick, but I noticed that I really don't know anything about flexbox. This is a great opportunity to find out.

I need a dropin minimal css framework just to do a quick fix in existing projects.

What I mostly need from a dropin css:

- layout (I have no idea why you would create a css framework without a layout, but there you have one of the reasons I needed this)
- positioning (flexbox)
- image util

But why stop there ..

- buttons
- typography
- basic reset (normalize is a bit much)

and whatever I in the future add

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
