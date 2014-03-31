## Fractions

##### Lightweight WIP Full Width Grid in Stylus

### The Grid

requires .col
```
.col
  display inline-block
  height auto
  width 100%
  padding 3%
  vertical-align top
  -webkit-box-sizing border-box /* Safari/Chrome, other WebKit */
  -moz-box-sizing border-box    /* Firefox, other Gecko */
  box-sizing border-box
```
Add a Fraction of the page:

```
.four-fifths
    width 80%

  .three-fourths
    width 75%

  .two-thirds
    width 66.6667%

  .fifth
    width 20%

  .fourth
    width 25%

  .third
    width 33.3333%

  .half
    width 50%
```
Its Mobile First so all widths start at 100% until the View Port reaches 720px
