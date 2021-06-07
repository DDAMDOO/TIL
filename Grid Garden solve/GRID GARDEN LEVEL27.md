# GRID GARDEN LEVEL27

##### `grid-template`은 `grid-template-rows`와 `grid-template-columns`를 조합한 단축 속성입니다.

##### 예를 들어, `grid-template: 50% 50% / 200px;`은 각각 50% 인 두개의 행(row)과 200px 너비의 한개의 열(column)의 그리드를 생성합니다.

##### `grid-template`을 사용하여 상단 60%와 왼쪽 200px를 포함하는 영역에 물을주세요.

```
#garden {
  display: grid;
  grid-template : 60% 40%/ 200px;
}

#water {
  grid-column: 1;
  grid-row: 1;
}
```

![level27](D:/git_repo/TIL/Grid Garden solve/assets/level27.png)

grid-template-columns와 grid-template-rows를 한 번에 하는 grid-template을 이용하여 행과 열의 값을 지정해주는 문제이다.

