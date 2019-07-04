# Grids
Unopinionated minimalist boilerplate for responsive 12-column style system.

**Minimalist Boilerplate**<br>
The code is written with minimalism in mind. The code itself is less than 100 lines. This code is enough to make your webpage responsive with 12-columns only. Half of the code is for responsiveness (damn you media queries!). Want only 12-column style system? You can strip some more code away!

**Responsive**<br>
Grids is designed to be responsive. It's dead simple. Everything in percent scales (or shrinks) even if you don't want to. Want to fix a width? Add your custom CSS and you are ready to go!

**Unopinionated**<br>
As Grids is a minimalist boilerplate, it comes only with the necessary code to make a responsive 12-column style system. You are on your own to add any styling you want to. In fact, the demo requires it's own styling to visually show that the demo actually works!

**Design Guide**<br>
The style system is based on 1200px design. Based on 4 device sizes, which are
- small (s, width<600px)
- medium (m, width<992px)
- large (l, width<1200px)
- extra large (xl, width>1200px).<br>

Column size starts from 6.33% and goes upto 98%. Width of an n-column grid can be calculated as `(n÷12*100)-2 %`. Columns have a gutter(margin) of 1% on each side.<br>
Columns have to be inside a row. Rows on the other hand can be directly inside the parent div(body) or inside a container.<br>
Container have a defined max-width of 1200px and is flexible as a percent of parent's width. Defined as 90% for small screen devices, 85% for medium screen devices and 75% for large and above screen devices.<br>
***NOTE:**<small>All widths are defined as a percentage of their parent's width, so be careful of nesting as elements may get small real quick.</small>*<br>

**No bullshit code**<br>
No classes for offset-, pull-, push-... code it straight and simple! Want an offset? Add an empty div with column of required offset.

**Naming convention**<br>
After working with a lot of css frameworks (Materialize, Bootstrap, UIKit, etc), the thing I liked most about Materialize was its naming convention for gird system, it is simple and clear. That is the same thing I borrowed from them as it is. So as far compatibility goes for grids system, Grids can work as drop in replacement for Materialize! (Although 1% margin would create some visual differences)

**Classes**<br>
The class name are as follows-<br>
`.container` - for creating a container<br>
`.row` - for creating a row<br>
`.col` - to define a column (size specific classes wouldn't work otherwise)<br>
`.s1-12`<br>
`.m1-12`<br>
`.l-12`<br>
`.xl1-12` for defining column size according to device screen size.
