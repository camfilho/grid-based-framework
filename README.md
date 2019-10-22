# Simple Grid Based Framework
This assignment consists of building a grid-based framework (similar to bootstrap) that includes some basic functionality necessary to build a website.

## Technologies Used
1. Saas
2. HTML/CSS

### The framework contains the next elements: 
[1. grid ](#Grid)<br>
[2. displays](#Displays)<br>
[3. positions](#Positions)<br>
[4. margins](#Margins)<br>
[5. paddings](#Padding)<br>
[6. Vertical alignment](#VerticalAlign)<br>
[7. Horizontal alignment](#HorizontalAlign)<br>
[8. background and text colors](#Colors)<br>
[9. Font Size](#Fsize)<br>
[9. Font weight](#Fweight)<br>


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
m-md-r-5 === margin-medium-right-5 the 5 === .5rem
m-lg-l-1 === margin-large-left-.1rem

## Paddings

is the same but start with p
p-sm-t-1 = padding-small-top-.1rem

## VerticalAlign

.text-v-align-top === vertical-align: top;

.text-v-align-bottom === vertical-align: bottom;

.text-v-align-center === vertical-align: middle;

## HorizontalAlign

.text-h-align-left === text-align: left;

.text-h-align-right === text-align: right;

.text-h-align-center ===  text-align: center;


## Colors

In Sass we can declare variables to reuse them in our code

$bg-secondary-color: white;

.bg-secondary-color {
  background-color: $bg-secondary-color; === white
}

## Fsize 

.text-size-xsmall === font-size: 10px;


.text-size-small ===  font-size: 12px;


.text-size-medium ===  font-size: 14px;


.text-size-large ===  font-size: 16px;


.text-size-xlarge ===  font-size: 18px;

## Fweight

.text-weight-b === font-weight: bold;

.text-weight-m === font-weight: medium;


.text-weight-n === font-weight: normal;

## html error 
Illegal character in query: | is not allowed.
we copy the link from google api


