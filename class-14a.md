# CSS Transforms, Transitions, and Animations

## Transforms
Reference: https://learn.shayhowe.com/advanced-html-css/css-transforms/

- comes in 2 different settings:
    1. 2D
    1. 3D

```
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```

## 2D Rotate

### HTML

```
<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>
```

### CSS

```
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}
```

## 2D Scale

### HTML

```
<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>
```

### CSS

```
.box-1 {
  transform: scale(.75);
}
.box-2 {
  transform: scale(1.25);
}
```
## 2D Cube

### HTML

```
<div class="cube">
  <figure class="side top">1</figure>
  <figure class="side left">2</figure>
  <figure class="side right">3</figure>
</div>
```

### CSS

```
.cube {
  position: relative;
}
.side {
  height: 95px;
  position: absolute;
  width: 95px;
}
.top {
  background: #9acc53;
  transform: rotate(-45deg) skew(15deg, 15deg);
}
.left {
  background: #8ec63f;
  transform: rotate(15deg) skew(15deg, 15deg) translate(-50%, 100%);
}
.right {
  background: #80b239;
  transform: rotate(-15deg) skew(-15deg, -15deg) translate(50%, 100%);
}
```

## Fade-In

### HTML

```
<!DOCTYPE html>
<html>
<head>
    <style type="text/css">
    </style>
</head>
<body>
    <div></div>
</body>
</html>
```

```
<style type="text/css">
body > div
{
            width:483px;
            height:298px;
            background:#676470;
            transition:all 0.3s ease;
}
</style>
```

### CSS

```
.fade
{
        opacity:0.5;
}
.fade:hover
{
        opacity:1;
}
```

## Change Color

### CSS

```
.color:hover
{
        background:#53a7ea;
}
```
## Grow & Shrink

### CSS (Grow)

```
.grow:hover
{
        -webkit-transform: scale(1.3);
        -ms-transform: scale(1.3);
        transform: scale(1.3);
}
```

### CSS (Shrink)

```
.shrink:hover
{
        -webkit-transform: scale(0.8);
        -ms-transform: scale(0.8);
        transform: scale(0.8);
}
```

## Rotate Elements

```
.rotate:hover
{
        -webkit-transform: rotateZ(-30deg);
        -ms-transform: rotateZ(-30deg);
        transform: rotateZ(-30deg);
}
```

## Square To Circle

```
.circle:hover
{
        border-radius:50%;
}

```


