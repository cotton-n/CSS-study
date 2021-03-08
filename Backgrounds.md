# Backgrounds

## Color

- `background-color: lightblue;`
- Opacity : 불투명도 => 0.0(투명) - 1.0(불투명) 사이 값
  - `opacity: 0.3;`
  - 불투명도 속성을 사용하면 모든 하위 요소들이 해당 속성을 상속받기 때문에 요소 내부에 텍스트를 읽기 어렵게 할 수 있다.
  - 자식 요소들이 상속받지 않도록 투명도를 조절하고 싶다면 `RGBA` 색상 값을 사용하면 된다!!  => `background: rgba(0, 128, 0, 0.3);`

---

## Image

- `background-image: url("paper.gif");`

  > When using  a background image, use an image that does not disturb the text.

---

## Repeat

- 기본적으로 background-image는 이미지를 수평 및 수직으로 반복
- 일부 이미지는 가로 또는 세로로만 반복해야 한다.
- `background-repeat: repeat-x;` => 수평으로만 반복 // 수직은 `repeat-y` // 한번만 표시는 `no-repeat`
- 이미지와 텍스트가 겹치는 문제가 발생할 수 있다.
- 배경 이미지의 위치를 지정하면 된다!! => `background-position: right top;`

---

## Attachment

- 배경 이미지를 스크롤할지 고정할지를 지정
- `background-attachment: fixed|scroll`

---

## Shorthand

- 코드를 줄이기 위해 Background 속성을 한번에 지정

  ```css
  body {
    background-color: #ffffff;
    background-image: url("img_tree.png");
    background-repeat: no-repeat;
    background-position: right top;
  }
  
  body {
    background: #ffffff url("img_tree.png") no-repeat right top;
  }
  ```

- 순서

  - Color Image Repeat Attachment Position -> 중간에 생략 가능

---

## ETC

- `background-clip` : 배경의 그림 영역 지정
- `background-origin` : 배경 이미지의 위치 지정  
- `background-size` : 배경 이미지의 크기 지정