# myCssMemos

设计闪烁效果

```css
animation: bnwBorder 1s linear infinite;  /*一秒，线性无限循环*/

@keyframes bnwBorder {
    0% {
        box-shadow: 0 0 10px #ffffff;
        background-color: #ffffff;
        color: #000000;
    }
    50% {
        box-shadow: 0 0 10px #000000;
        background-color: #efefef;
        color: #000000;
        transform: scale(1.02);
    }
    100% {
        box-shadow: 0 0 10px #ffffff;
        background-color: #ffffff;
        color: #000000;
    }
}
```
