# css
一些未形成标准的css特性

### 文字渐变
```css
.text-gradient {
    background-image: -webkit-gradient(linear, 0 0, 0 bottom, from(rgba(255, 243, 217, 1)), to(rgba(233, 145, 76, 1)));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
```
