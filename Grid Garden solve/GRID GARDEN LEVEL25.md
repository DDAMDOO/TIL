# GRID GARDEN LEVEL25

##### 이제 당신의 정원 왼쪽 75px에 잡초가 있습니다. 나머지 공간의 3/5에는 당근이 자라고 있으며, 반대인 2/5에는 잡초가 넘치고있습니다.

##### `grid-template-columns`를 `px`와 `fr`단위와 함께 사용하여 필요한 열(column)을 만드세요.

```
#garden {
  display: grid;
  grid-template-columns : 75px 3fr 2fr;
  grid-template-rows: 100%;
}
```

![level25](D:/git_repo/TIL/Grid Garden solve/assets/level25.png)

문제에 주어진대로 픽셀과 fr을 이용하여 나누면 되는 문제이다.

