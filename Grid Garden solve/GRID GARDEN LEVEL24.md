# GRID GARDEN LEVEL24

##### 열(column)을 pixel, percentage, 혹은 ems로 설정시, `fr`로 설정된 다른 열(column)의 남은 공간으로 나뉘어집니다.

##### 여기에 당근은 왼쪽에 50px, 잡초는 오른쪽에 50px로 되어있습니다. `grid-template-columns`를 사용하여 2개의 열(column), 그리고 `fr`를 사용하여 나머지 공간을 차지하는 3개의 열(column)까지 만들어보세요.

```
#garden {
  display: grid;
grid-template-columns: 50px 1fr 1fr 1fr 50px;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-area: 1 / 1 / 6 / 2;
}

#poison {
  grid-area: 1 / 5 / 6 / 6;
}
```

![level24](D:/git_repo/TIL/Grid Garden solve/assets/level24.png)

이 문제에 대해서는 해결하는 데 문제 이해를 제대로 하지 못해서 오래걸렸는데, 양 끝에 50px을 고정으로 하고, 이미 나누어진 칸이 5칸이므로 1fr을 3개 넣어서 지정해주어야 한다.