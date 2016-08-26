# freeform.css
simple scalable CSS utility library for rapid prototyping

```sh
npm install freeform.css --save
```

## Classes

### `.aid`
hide content for screenreaders
```css
.aid {
  clip: rect(0 0 0 0);
  overflow: hidden;
  position: absolute;
  width: 1px;
  height: 1px;
  border: 0;
  margin: -1px;
  padding: 0; }
```

### `.clearfix`
clearfix floats
```css
.clearfix::after {
  clear: both;
  content: "";
  display: table; }
```

### `.reset`

```css
.reset {
  margin: 0;
  border: 0;
  padding: 0;
  list-style-type: none; }
```

##### reset specific box-model properties
```css
.no-margin {
  margin: 0; }

.no-border {
  border: 0; }

.no-padding {
  padding: 0; }
```

### `.auto-margin`
```css
.auto-margin {
  margin-left: auto;
  margin-right: auto; }
```

### `position`
```css
.position-middle {
  position: absolute;
  top: 50%;
  transform: translateY(-50%); }
```

```css
.position-relative {
  position: relative; }
  
.position-absolute {
  position: absolute; }
  
.position-fixed {
  position: fixed; }
```

### `float`
```css
.float-left {
  float: left; }

.float-right {
  float: right; }

.float-none {
  float: none; }
```

### `clear`
```css
.clear-left {
  clear: left; }

.clear-right {
  clear: right; }

.clear-both {
  clear: both; }
```

### `display`
```css
.display-block {
  display: block; }

.display-inline {
  display: inline; }

.display-inline-block {
  display: inline-block; }

.display-table {
  display: table; }

.display-none {
  display: none; }
```

### text
```css
.text-hidden {
  font: 0/0; }

.text-inherit {
  text-decoration: inherit;
  line-height: inherit;
  font-size: inherit;
  font-style: inherit;
  font-weight: inherit;
  font-family: inherit;
  font-variant: inherit; }

.text-lighter {
  font-weight: lighter; }

.text-bold {
  font-weight: bold; }

.text-bolder {
  font-weight: bolder; }

.text-center {
  text-align: center; }

.text-left {
  text-align: left; }

.text-right {
  text-align: right; }

.text-middle {
  vertical-align: middle; }
```

## License
MIT
