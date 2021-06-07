# GRID GARDEN LEVEL22

##### `grid-template-columns`은 백분율 같은 값뿐만 아니라, 픽셀 및 em과 같은 길이 단위도 허용합니다. 또한 서로 다른 단위를 함께 사용할 수도 있습니다.

##### 해당 정원에 3개 열을 각각 `100px`, `3em` 및 `40%`로 설정해보세요.

```
#garden {
  display: grid;
  grid-template-columns: 100px 3em 40%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}
```

![level22](D:/git_repo/TIL/Grid Garden solve/assets/level22.png)

문제에 나와있는 대로  열의 값을 px, em, %와 같은 다양한 단위로 사용 가능하다.

