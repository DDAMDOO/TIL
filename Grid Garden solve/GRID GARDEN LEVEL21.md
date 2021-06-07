# GRID GARDEN LEVEL21

##### 동일한 너비의 열(column)들을 지정할려면 불편할 수 있습니다. 다행스럽게도 a `repeat` 함수가 이 문제를 해결해줍니다.

##### 예를 들면, `grid-template-columns: 20% 20% 20% 20% 20%;`와 같이 이전에는 설정했었지만, `grid-template-columns: repeat(5, 20%);`와 같이 설정해도 동일합니다.

##### `grid-template-columns`과 함께 `repeat` 함수를 사용하여, 8개의 12.5% 동일한 너비를 가진 열을 만들어보세요. 이렇게하면 당신은 물을 더 낭비하지 않게됩니다.

```
#garden {
  display: grid;
  grid-template-columns : repeat(8, 12.5%);
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-column: 1;
  grid-row: 1;
}
```

![level21](D:/git_repo/TIL/Grid Garden solve/assets/level21.png)

같은 비율로 반복할 경우 repeat 함수를 이용하여서 쉽게 구간을 설정할 수 있다.

