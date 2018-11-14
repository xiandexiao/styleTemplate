hoverSpread
===============
> 添加伪元素
```
.input-parent:after{
            content: "";
            width: 0;
            height: 2px;
            background: #fd922b;
            position: absolute;
            bottom: 10px;
            left: 50%;
            transition: all 1s;
        }
 @keyframes all {
    0%{width: 0;left:50%}
    100%{width: 70%;left:2rem}
}
.input-parent:hover:after{
    left:0;
    width:100%;
}
```
