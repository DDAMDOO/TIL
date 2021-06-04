# GRID GARDEN LEVEL8

##### 다시한번 `grid-column-end`에 `span`을 이용하여 당근에 물을 주십시오.

```css
#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-column-start: 1;
  grid-column-end : span 5;
}
```

![level8](D:/git_repo/TIL/Grid Garden solve/assets/level8.png)

level7과 마찬가지로 span을 이용하여 해결하면 된다.