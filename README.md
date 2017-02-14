# freeform.css
Functional expressive CSS for rapid prototyping

```
npm install freeform.css --save
```

## API
Supply space-separated values to `[data-freeform]`

### clearfix
```
<p data-freeform="clearfix">
```

### reset
```
<ul data-freeform="reset">
```

### no
```
<fieldset data-freeform="no--margin no--border no--padding">
```

### align
```
<div data-freeform="align--auto">align auto</div>
<div data-freeform="align--x">align horizontal</div>
<div data-freeform="align--y">align vertical</div>
<div data-freeform="align--xy">align both</div>
```

### position
```
<p data-freeform="position--static">
<p data-freeform="position--relative">
<p data-freeform="position--absolute">
<p data-freeform="position--fixed">
<p data-freeform="position--sticky">
```

### float
```
<p data-freeform="float--left">
<p data-freeform="float--right">
<p data-freeform="float--none">
```

### clear
```
<p data-freeform="clear--left">
<p data-freeform="clear--right">
<p data-freeform="clear--both">
```

### display
```
<p data-freeform="display--inline">
<p data-freeform="display--inline-block">
<p data-freeform="display--block">
<p data-freeform="display--table">
<p data-freeform="display--none">
```

### text
```
<p data-freeform="text--hidden">
<p data-freeform="text--inherit">
<p data-freeform="text--lighter">
<p data-freeform="text--bold">
<p data-freeform="text--bolder">
<p data-freeform="text--center">
<p data-freeform="text--left">
<p data-freeform="text--right">
<p data-freeform="text--middle">
```
