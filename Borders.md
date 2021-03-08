# Borders

```css
p.dotted {border-style: dotted;}
p.dashed {border-style: dashed;}
p.solid {border-style: solid;}
p.double {border-style: double;}
p.groove {border-style: groove;}
p.ridge {border-style: ridge;}
p.inset {border-style: inset;}
p.outset {border-style: outset;}
p.none {border-style: none;}
p.hidden {border-style: hidden;}
p.mix {border-style: dotted dashed solid double;}
```

![image-20210309001321704](C:\Users\yejiH\AppData\Roaming\Typora\typora-user-images\image-20210309001321704.png)



## Width

선 굵기 지정 (**px, pt, cm, em, etc** | **thin, medium, or thick**)

- Specific Side Widths

  > 상하좌우 다른 굵기 지정 가능

  ```css
  p.one {
    border-style: solid;
    border-width: 5px 20px; /* 5px top and bottom, 20px on the sides */
  }
  
  p.two {
    border-style: solid;
    border-width: 20px 5px; /* 20px top and bottom, 5px on the sides */
  }
  
  p.three {
    border-style: solid;
    border-width: 25px 10px 4px 35px; /* 25px top, 10px right, 4px bottom and 35px left */
  }
  ```

  

## Color

- **name** - red
- **HEX** - #fff
- **RGB** - rgb(255, 0, 0)
- **HSL** - hsl(0, 100%, 50%)
- **transparent**

>  상하좌우 다른 색 지정 가능



## Sides

- 4 values
  - `border-style: (top) (right) (bottom) (left)`
- 3 values
  - `border-style: (top) (right&left) (bottom)`
- 2 values
  - `border-style: (top&bottom) (right&left)`

- 1 values 
  - `border-style: (all)`



## Shorthand

- `border-width`
- `border-style` (required)
- `border-color`

```css
p {
  border: 5px solid red;
}
```



## Radius

The `border-radius` property is used to add rounded borders to an element

```css
p {
  border: 2px solid red;
  border-radius: 5px;
}
```

