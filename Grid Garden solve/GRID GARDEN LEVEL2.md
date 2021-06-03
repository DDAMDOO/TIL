# GRID GARDEN LEVEL2

##### 저런, 정원에 잡초가 자라고 있습니다. `grid-column-start`을 사용하여 잡초를 제거하세요. 잡초는 5번째 열(column)에서 자라고 있습니다.

```css
#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#poison {
grid-column-start : 5;
}
```

![level2](.\assets\level2.png)

level 1과 마찬가지로 grid-column-start : 5; 이라는 속성을 부여하여서 물의 위치를 바꾸는 것으로 해결할 수 있다.

