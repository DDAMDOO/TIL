# GRID GARDEN LEVEL3

##### `grid-column-start`이 단독으로 사용될때는, 한개의 그리드 열(column)을 나타냅니다. 하지만, `grid-column-end` 속성을 같이 사용하면 여러 열(column)에 걸쳐 확장이 가능합니다.

##### `grid-column-end`를 이용하여, 먼지를 피해 모든 당근에 물을 주세요. 물이 낭비되지 않도록 주의하세요! 당근은 첫번째 수직선에서 네번째 수직선까지 이어져있습니다.

```css
#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-column-start: 1;
grid-column-end : 4;
}
```

![level3](../assets/level3.png)

이번에는 시작점과 끝나는 지점을 선정하는 문제이다. 처음에는 4 라는 숫자에 대해서 의문이 있었는데 칸에 대한 인덱스가 아닌 가로선에 대한 인덱스이다. 이 점을 유의하여 문제를 풀면 된다.

