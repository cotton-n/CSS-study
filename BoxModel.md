# Box Model

![image-20210309152359898](C:\Users\yejiH\AppData\Roaming\Typora\typora-user-images\image-20210309152359898.png)

- **Content** - The content of the box, where text and images appear
- **Padding** - Clears an area around the content. The padding is transparent
- **Border** - A border that goes around the padding and content
- **Margin** - Clears an area outside the border. The margin is transparent



> In order to set the width and height of an element correctly in all browsers, you need to know how the box model works.



```css
div {
  width: 320px;
  padding: 10px;
  border: 5px solid gray;
  margin: 0;
}
```

=> 실제 너비는 350px