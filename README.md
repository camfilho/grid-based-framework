# Simple Grid Based Framework
This assignment consists of building a grid-based framework (similar to bootstrap) that includes some basic functionality necessary to build a website.

## we made a grid framework similar to bootstrap
we used sass to increase our productivity

### the framework contains the next elements: 
[1. grid ](#Grid)
[2. displays](#Displays)
[3. positions](#Positions)
[4. margins](#Margins)
[5. paddings](#Padding)
[6. Vertical alignment](#Valign)
[7. Horizontal alignment](#Halign)
[8. background and text colors](#Colors)
[9. Font Size](#Fsize)
[9. Font weight](#Fweight)


## Grid

> Use our powerful mobile-first flexbox grid to build layouts of all shapes and sizes thanks to a twelve column system.

### How it Works?
Our grid system uses a series of containers, rows, and columns to layout and align content. It’s built with flexbox and is fully responsive.

```html
<div class="container-fluid">
  <div class="row">
    <div class="col--sm-4">
      One of three columns
    </div>
    <div class="col--sm-4">
      One of three columns
    </div>
    <div class="col--sm-4">
      One of three columns
    </div>
  </div>
</div>
```
With the above snippet, it creates a row with 3 columns.<br>
In general, there are 3 breakdowns for grid layout:
1. Small
col--sm-1 up to col--sm--12
2. Medium
col--md-1 up to col--md--12
3. Large
col--lg-1 up to col--lg--12

## Displays
class="d-float" = display: float;
class="float-right || left" = float: right || left;

## Positions 
class= "pos-relative" = position: relative;
the same with: 
pos-absolute 
pos-fixed

## Margins
m-sm-t-(n<10) === margin-small-top-3 | goes from 0 rem to 1 rem
m-md-r-5 ===