# freeform.css
Functional expressive CSS for rapid prototyping

```
npm install freeform.css --save
```

## API

### clearfix
clearfix floats
```css
[data-freeform~="clearfix"]::after {
  clear: both;
  content: "";
  display: table; }
```

### reset
```css
[data-freeform~="reset"] {
  margin: 0;
  border: 0;
  padding: 0;
  list-style-type: none; }
```

### box model
```css
[data-freeform~="no-margin"] {
  margin: 0; }

[data-freeform~="no-border"] {
  border: 0; }

[data-freeform~="no-padding"] {
  padding: 0; }
```

### auto-margin
```css
[data-freeform~="auto-margin"] {
  margin-left: auto;
  margin-right: auto; }
```

### position
```css
[data-freeform~="position-middle"] {
  position: absolute;
  top: 50%;
  transform: translateY(-50%); }
```

```css
[data-freeform~="position-relative"] {
  position: relative; }

[data-freeform~="position-absolute"] {
  position: absolute; }

[data-freeform~="position-fixed"] {
  position: fixed; }
```

### float
```css
[data-freeform~="position-relative"] {
  position: relative; }

[data-freeform~="position-absolute"] {
  position: absolute; }

[data-freeform~="position-fixed"] {
  position: fixed; }
```

### clear
```css
[data-freeform~="clear-left"] {
  clear: left; }

[data-freeform~="clear-right"] {
  clear: right; }

[data-freeform~="clear-both"] {
  clear: both; }
```

### `display`
```css
[data-freeform~="display-block"] {
  display: block; }

[data-freeform~="display-inline"] {
  display: inline; }

[data-freeform~="display-inline-block"] {
  display: inline-block; }

[data-freeform~="display-table"] {
  display: table; }

[data-freeform~="display-none"] {
  display: none; }
```

### text
```css
[data-freeform~="text-hidden"] {
  font: 0/0; }

[data-freeform~="text-inherit"] {
  text-decoration: inherit;
  line-height: inherit;
  font-size: inherit;
  font-style: inherit;
  font-weight: inherit;
  font-family: inherit;
  font-variant: inherit; }

[data-freeform~="text-lighter"] {
  font-weight: lighter; }

[data-freeform~="text-bold"] {
  font-weight: bold; }

[data-freeform~="text-bolder"] {
  font-weight: bolder; }

[data-freeform~="text-center"] {
  text-align: center; }

[data-freeform~="text-left"] {
  text-align: left; }

[data-freeform~="text-right"] {
  text-align: right; }

[data-freeform~="text-middle"] {
  vertical-align: middle; }
```
