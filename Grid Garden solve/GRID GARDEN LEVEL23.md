# GRID GARDEN LEVEL23

##### 또한 Grid는 새로운 단위인 fractional `fr`를 소개하고 있습니다. 각 `fr` 단위들은 사용가능한 공간을 하나로 공유하여 할당합니다. 예시로, 두개의 element들을 `1fr`과 `3fr`로 설정시, 공간이 4개의 동일한 크기로 공유됩니다. 첫번째 element는 사용가능한 공간의 1/4 크기로 그리고 두번째 element는 3/4 크기를 차지합니다.

##### 여길보면 잡초가 첫 번째 줄의 1/6를 차지하고 있고 당근은 나머지 5/6를 차지하고 있습니다. `fr` 단위를 사용하여 이 너비로 두 개의 열을 만들어보세요.

```
#garden {
  display: grid;
grid-template-columns: 1fr 5fr;
  grid-template-rows: 20% 20% 20% 20% 20%;
}
```

![level23](D:/git_repo/TIL/Grid Garden solve/assets/level23.png)

fractional 이라는 단위를 통해서 총 해당fr을 총 fr로 나눈 비율만큼으로 나눌 수 있다.