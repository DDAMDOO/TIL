# GRID GARDEN LEVEL18

##### 그리드 요소들이 `grid-area`, `grid-column`, `grid-row`, 기타 등을 사용하지 않고, 표시될 경우 소스코드에 기입된 순서대로 표기됩니다. table 레이아웃에 비해 grid 시스템의 장점인 `order` 속성을 이용하면 이를 재정의가 가능합니다.

##### 기본적으로, 그리드의 모든 요소들은 `order`의 값이 0이지만, `z-index`와 같이 양수와 음수의 값 모두 설정이 가능합니다.

##### 지금 바로, poison의 `order`를 변경하여 두번째 열에 있는 당근에 물을 주고 마지막 열에 있는 잡초를 제거하세요.

```
#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

.water {
  order: 0;
}

#poison {
  order : 1;
}
```

![level18](D:/git_repo/TIL/Grid Garden solve/assets/level18.png)

해당 옵션들의 순서를 정하는 order를 통해서 물의 위치를 변경 가능했다.