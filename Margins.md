# Margins

요소 바깥쪽 공백

- **auto** - the browser calculates the margin
- ***length*** - specifies a margin in px, pt, cm, etc.
- ***%*** - specifies a margin in % of the width of the containing element
- **inherit** - specifies that the margin should be inherited from the parent element



 ## Auto Value

너비를 지정하고 auto 속성을 지정하면 수평으로 중앙에 배치 가능

```css
div {
  width: 300px;
  margin: auto;
  border: 1px solid red;
}
```



## Inherit Value

```css
/* 부모 속성 */
div {
  border: 1px solid red;
  margin-left: 100px;
}

/* 자식 속성 */
p.ex1 {
  margin-left: inherit; // => margin-left: 100px;
}
```



## Margin Collapse

```css
h1 {
  margin: 0 0 50px 0;
}

h2 {
  margin: 20px 0 0 0;
}
```

> h1의 아래쪽 여백이 50px이고 h2의 위쪽 여백이 20px이다. 위와 아래를 합쳐서 70px의 여백이 있어야하지만 둘 중 더 큰 여백인 50px로 지정되는데 이것은 Margin Collapse 라고 한다.