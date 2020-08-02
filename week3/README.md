# 3주차. CSS Layout 이해하기

### 0. 들어가며
출처 : http://roadmap.sh/frontend
그 중 CSS 파트의 Making Layouts 내용입니다. 

- Floats
- Positioning
- Display
- Box Model
- Css Grid
- Flex Box

---

### 1. Floats
링크 : https://www.w3schools.com/cssref/playit.asp?filename=playcss_float&preval=left

- The CSS `float` property specifies how an element should float. 
- 글보다는 이미지에서 많이 사용되는 property인 것 같습니다. 

```cSS
float: left;
float: right;
```

---

### 2. Positioning

링크 : [https://electronic-moongchi.tistory.com/26#:~:text=relative%20%3A%20%EC%9C%84%EC%B9%98%EB%A5%BC%20%EA%B3%84%EC%82%B0%ED%95%A0%EB%95%8C,%EC%9C%84%EC%B9%98%EB%A5%BC%20%EC%A7%80%EC%A0%95%ED%95%A0%20%EC%88%98%20%EC%9E%88%EB%8B%A4.](https://electronic-moongchi.tistory.com/26#:~:text=relative %3A 위치를 계산할때,위치를 지정할 수 있다.)

```css
position: static;
position: relative;
position: fixed;
position: absolute;
position: sticky;
```

* static : top/bottom/left/right 아무리 설정해서 다르게 positioning 하려고 해도 움직이지 않는다. 
* relative : static 했을 때 나오는 위치로부터 ~ 
* absolute : 가장 붙어있는 요소로부터 ~
* fixed : 스크롤에 상관없이 동일한 자리 유지
* sticky : 초반에는 스크롤 내리면 함께 올라가다가 화면 밖으로 갈 때 쯤에 fixed 처럼 됨. 

---

### 3. Display

사실, `display: ` 에는 `display: grid;` 도 있고, `display: flex;`  도 있다. display property에서는 어떤 것처럼 보여줄 것인가에 초점을 둔다. 

```css
display: inline;
display: block;
```

* inline : 앞 뒤 글 내용과 함께 흘러가는 것처럼
* block : 앞 뒤 글 사이에 엔터 쳐서 새로운 블록을 만든다.

---

### 4. Box Model

---

### 5. Grid

링크 : https://www.w3schools.com/css/css_grid.asp

* `display: grid;` 로 시작하며, `display: flex;` 와 같이 container - item 간의 관계로 나타낸다. flex는 item의 가로 정렬 방식을 위주로 나타낸다면, grid는 item을 표처럼 나타낸다. 

![img](https://www.w3schools.com/css/grid_lines.png)

