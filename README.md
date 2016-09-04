# Grid Object #

The grid object is responsible for building a smart grid when used with [Size](https://github.com/iotacss/utilities.size), [Push](https://github.com/iotacss/utilities.push) or [Pull](https://github.com/iotacss/utilities.push) utilities.


### Installation ###

```
npm install --save iotacss-grid
```


### Dependencies ###

* [Settings.Default](https://github.com/iotacss/settings.default)


### Options ###

```
$iota-grid--aligned       : false !default;
$iota-grid--rev           : false !default;
$iota-grid-gutter-default : 20px !default;
$iota-grid-gutter-extra   : () !default;
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
