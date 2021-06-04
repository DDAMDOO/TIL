# GRID GARDEN LEVEL12

##### flexbox와 별개로 CSS 그리드를 설정하면 컬럼과 행 두가지 측면에서 쉽게 그리드 항목을 배치할 수 있습니다. `grid-row-start`는 `grid-column-start` 수직선을 제외하곤 동일하게 작동합니다.

##### `grid-row-start`를 이용하여 당근에 물을 주십시오.

```
#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-row-start : 3;
}
```

![level12](./assets/level12.png)

여태까지 column을 이용한 조작이었다고 하면 이번엔 row를 이용한 조작을 하여 문제를 해결하면 된다.