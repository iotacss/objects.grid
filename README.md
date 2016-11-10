# Grid Object #

The grid object is responsible for building a smart grid when used with [Size](https://github.com/iotacss/utilities.size), [Push](https://github.com/iotacss/utilities.push) or [Pull](https://github.com/iotacss/utilities.push) utilities.


### Installation ###

```
npm install --save iotacss-obj-grid
```


### Options ###

```sass
$iota-obj-grid-namespace          : 'grid' !default;
$iota-obj-grid-column-name        : 'col' !default;
$iota-obj-grid-align-right-name   : 'right' !default;
$iota-obj-grid-align-center-name  : 'center' !default;
$iota-obj-grid-align-top-name     : 'top' !default;
$iota-obj-grid-align-middle-name  : 'middle' !default;
$iota-obj-grid-align-bottom-name  : 'bottom' !default;
$iota-obj-grid-align-around-name  : 'around' !default;
$iota-obj-grid-align-between-name : 'between' !default;
$iota-obj-grid-reverse-name       : 'rev' !default;
$iota-obj-grid-equal-height-name  : 'equal-height' !default;

$iota-obj-grid-gutter-default     : $iota-global-gutter-default !default;
$iota-obj-grid-gutter-extra       : () !default;

$iota-obj-grid-aligned            : false !default;

$iota-obj-grid-rev                : false !default;

$iota-obj-grid-flex               : $iota-global-flex !default;
$iota-obj-grid-equal-height       : false !default;
```


### Example

```html
<div class="o-grid">

    <div class="o-grid__col u-1/2">
      Column 1
    </div><!--

 --><div class="o-grid__col u-1/2">
      Column 2
    </div>

</div>
```

Do you see this empty HTML comment '<!-- -->'? This is used to fight the space between the grid columns, because they are inline block elements. If you want to read more about this fix or find some alternatives, head over [here](https://css-tricks.com/fighting-the-space-between-inline-block-elements/).
