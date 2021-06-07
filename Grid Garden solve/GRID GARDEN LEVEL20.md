# GRID GARDEN LEVEL20

##### 지금까지의 정원은 열(column)과 행(row)이 각각 20% 너비의 5개 요소로 설정되어있습니다.

##### 이 설정은 `grid-template-columns: 20% 20% 20% 20% 20%;`과 `grid-template-rows: 20% 20% 20% 20% 20%;`로 각 속성에는 5개의 열을 만드는 5개 값이 있으며, 각 열은 정원의 20% 너비 설정되었습니다.

##### 하지만 지금부터는 그리드의 설정을 원하는대로 설정할 수 있습니다. `grid-template-columns`를 새로운 값을 설정하여 당근에 물을 주세요. 첫번째 열(column)의 넓이를 50%로 설정하세요.

```
#garden {
  display: grid;
  grid-template-columns : 50%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-column: 1;
  grid-row: 1;
}
```

![level20](D:/git_repo/TIL/Grid Garden solve/assets/level20.png)

이번엔 화면 전체의 비율을 변경하는 문제이다. columns의 값을 50%로 지정하여 문제를 해결할 수 있다.

