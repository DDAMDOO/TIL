# FLEXBOX FROGGY LEVEL2

##### `justify-content`를 한 번 더 사용하여 개구리들이 수련잎으로 이동하는 것을 도와주세요. 이 CSS 속성은 요소들을 가로선 상에서 정렬하며 다음의 값들을 인자로 받는다는 것을 기억하세요:

- ##### `flex-start`: 요소들을 컨테이너의 왼쪽으로 정렬합니다.

- ##### `flex-end`: 요소들을 컨테이너의 오른쪽으로 정렬합니다.

- ##### `center`: 요소들을 컨테이너의 가운데로 정렬합니다.

- ##### `space-between`: 요소들 사이에 동일한 간격을 둡니다.

- ##### `space-around`: 요소들 주위에 동일한 간격을 둡니다.

```css
#pond {
  display: flex;
  justify-content : center;
}
```

![image-20210608132148625](D:\git_repo\TIL\Flexbox Froggy\assets\image-20210608132148625.png)

해당 문제는 설명에서도 나온 것 처럼 justify-content : center를 통해서 element를 가운데 정렬하여 해결할 수 있다.