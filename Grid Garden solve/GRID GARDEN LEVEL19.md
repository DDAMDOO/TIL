# GRID GARDEN LEVEL19

##### 모든 잡초가 정원의 맨앞에 위치해 있으며, 물과 독은 교대로 위치해 있습니다. poison의 `order`를 변경하여 정원을 정리해봅시다.

```
#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

.water {
  order: 0;
}

.poison {
  order : -1;
}
```

![level19](D:/git_repo/TIL/Grid Garden solve/assets/level19.png)

이미 order를 0으로 준 것이 있기 때문에 이보다 빠르게 하기 위해 음수 값을 지정해주었다.