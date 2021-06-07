# GRID GARDEN LEVEL28

##### 당신의 정원은 멋지다. 여기 정원 바닥 50px을 남겨두고 나머지 모두를 당근으로 채웠습니다.

##### 불행하게도, 당신의 당근 왼쪽 20%는 잡초로 우거져 있습니다. 정원의 치료를 위해 CSS grid를 사용해보시기 바랍니다.

```
#garden {
  display: grid;
  grid-template : 1fr 50px/20% 80%;
}
```

![level28](D:/git_repo/TIL/Grid Garden solve/assets/level28.png)

row에 해당하는 부분은 px을 함께 써야 하기 때문에 fr로 지정해주고 columns는 20% 80%로 비율을 나누어 주면 해결 가능하다.

