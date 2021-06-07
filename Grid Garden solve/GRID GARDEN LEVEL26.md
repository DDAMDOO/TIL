# GRID GARDEN LEVEL26

##### `grid-template-rows`은 `grid-template-columns`와 거의 동일하게 작동합니다.

##### `grid-template-rows`을 사용하여 정원 상단의 50px를 제외하고 물을 주세요. 물이 5번째 행(row)만 설정되어있으므로, 5개의 행(row)을 생성해야합니다.

```
#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
grid-template-rows: 50px 0fr 0fr 0fr 1fr;
}

#water {
  grid-column: 1 / 6;
  grid-row: 5 / 6;
}
```

![level26](D:/git_repo/TIL/Grid Garden solve/assets/level26.png)

columns를 만들었던 방식과 같이 만들면된다. 여기서는 총 5칸으로 나누어야 하기 때문에 가운데 3개는 빈 fr로 만들어 물을 채울 수 있도록 한다.

