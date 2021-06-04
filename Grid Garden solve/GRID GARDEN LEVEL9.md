# GRID GARDEN LEVEL9

##### 또한 `span` keyword와 `grid-column-start`를 이용하여 마지막 위치에서 상대적으로 항목의 넓이를 설정이 가능합니다.

```css
#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-column-start : span 3;
  grid-column-end: 6;
}
```

![level9](D:/git_repo/TIL/Grid Garden solve/assets/level9.png)

column-end를 지정하고 start 지점에 span을 이용하여서도 문제를 해결할 수 있다.