# Padding

요소 안쪽 공백

- ***length*** - specifies a padding in px, pt, cm, etc.
- ***%*** - specifies a padding in % of the width of the containing element
- **inherit** - specifies that the padding should be inherited from the parent element



## Padding and Element Width

```css
div {
  width: 300px;
  padding: 25px;
}
```

> 실제 width는 300px + 25px + 25px = 350px
>
> 바람직하지 않은 결과😥

```css
div {
  width: 300px;
  padding: 25px;
  box-sizing: border-box;
}
```

> box-sizing을 이용하면 width는 고정되고 padding값이 늘어나면 내부 content의 너비가 줄어듬