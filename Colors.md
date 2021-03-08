# Colors

>  색상은 `Color Names`, `RGB`, `HEX`,` HSL`, `RGBA`,` HSLA` 값을 사용

## Colors

- Color Names
  - Orange
  - LightGray                   ...CSS/HTML support 140 standard color names

- Backgroung Color => `background-color:DodgerBlue;`
- Text Color => `color: Tomato;`
- Border Color => `border: 1px solid Violet;`
- Color Values
  - `rgb(255, 99,71)` = `#ff6347` = `hsl(9, 100%, 64%)` = `Tomato`
  - 50% transparent => 투명도 지정
    - `rgba(255, 99,71, 0.5)` = `hsla(9, 100%, 64%, 0.5)`

---

## RGB

- `rgb(red, green, blue)` => 각 값은 0 - 255 사이 값
- `rgba(red, grren, blue, alpha)` => alpha의 경우 0(투명도 100) - 1(투명도 0) 사이 값

---

## HEX

- `#rrggbb` => 16진수 값
- 3 Digit HEX Value
  - `#rgb` : 예를 들어 `#ff00aa` => `#f0a`

---

## HSL

- `hsl(hue, saturation, lightness)` 
  - Hue : degree on the color wheel from 0 -360
    - ex) `0 => red`, `120 => green`,` 240 => blue`
  - Saturation : percentage value
    - ex) `0% => shade of green`, `100% => full color`  
  - Lightness : percentage value
    - ex) `0% => black`, `50% => neither light or dark`, `100% => white`
- `hsla(hue, saturation, lightness, alpha)` => alpha의 경우 0(투명도 100) - 1(투명도 0) 사이 값