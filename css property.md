## css 텍스트

CSS에는 텍스트 서식을 지정하는 많은 속성이 있다.

### 텍스트 색상
color속성은 텍스트의 색상을 설정하는 데 사용됩니다.

```
h1 {
  color: green;
}
```

### 텍스트 정렬

text-align속성은 텍스트의 수평 정렬을 설정하는 데 사용됩니다.

```
h1 {
  text-align: center;
}
h2 {
  text-align: left;
}
h3 {
  text-align: right;
}
```


## css 링크

CSS를 사용하면 다양한 방식으로 링크의 스타일을 지정할 수 있다.

링크는 상태 에 따라 다르게 스타일을 지정할 수 있다.
네 가지 링크 상태는 다음과 같다:

<li>a:link - 방문하지 않은 정상적인 링크</li>
<li>a:visited - 사용자가 방문한 링크</li>
<li>a:hover - 사용자가 마우스를 가져가면 링크</li>
<li>a:active - 클릭하는 순간 링크</li>

```
/* unvisited link */
a:link {
  color: red;
}

/* visited link */
a:visited {
  color: green;
}

/* mouse over link */
a:hover {
  color: hotpink;
}

/* selected link */
a:active {
  color: blue;
}
```


## css 플로트

이 float속성은 콘텐츠의 위치를 지정하고 서식을 지정하는 데 사용된다.

float속성은 다음 값 중 하나를 가질 수 있다 

<li>left - 요소는 컨테이너의 왼쪽에 떠 있습니다.</li>
<li>right - 요소는 컨테이너의 오른쪽에 떠 있습니다.</li>
<li>none- 요소는 부동하지 않습니다(텍스트에서 발생하는 바로 그곳에 표시됩니다). 이것은 기본값입니다</li>
<li>inherit - 요소는 부모의 float 값을 상속합니다.</li>

<p><img src="https://velog.velcdn.com/images%2Fsanna422%2Fpost%2F752f592e-582d-47b7-9ced-4c58cdccad6d%2Fimage.png" alt="css 플로트"></p>


```
div {
  float: left;
  padding: 15px; 
}

.div1 {
  background: red;
}

.div2 {
  background: yellow;
}

.div3 {
  background: green;
}
```


### 텍스트 장식

text-decoration속성은 텍스트에서 설정 제거를 장식하는 데 사용됩니다.

```
h1 {
  text-decoration: overline;
}
h2 {
  text-decoration: line-through;
}
h3 {
  text-decoration: underline;
}
```

### 텍스트 변환

text-transform속성은 대문자와 텍스트에서 소문자를 지정하는 데 사용됩니다.

```
p.uppercase {
  text-transform: uppercase;
}
p.lowercase {
  text-transform: lowercase;
}
p.capitalize {
  text-transform: capitalize;
}
```


## css 배경색상

<p><img src="https://velog.velcdn.com/images%2Fsanna422%2Fpost%2Fbb940cfa-6410-411a-aaa6-8d3b0a7be8c7%2Fimage.png" alt="css 배경 색상"></p>

```
<h1 style="background-color:DodgerBlue;">Hello World</h1>
```

## css 텍스트 색상

<p><img src="https://velog.velcdn.com/images%2Fsanna422%2Fpost%2Fb4cad8d7-17f9-45c9-b5ea-f291d4405ba0%2Fimage.png" alt="css 텍스트 색상"></p>

```
<p style="color:DodgerBlue;">Lorem ipsum...</p>
```

## css 테두리 색상

<p><img src="https://velog.velcdn.com/images%2Fsanna422%2Fpost%2F2257da01-8f78-4490-8f95-3ed15e4d7eb5%2Fimage.png" alt="css 테두리 색상"></p>

```
<h1 style="border:2px solid Violet;">Hello World..</h1>
```

## css 색상 값

CSS에서는 RGB 값, HEX 값, HSL 값, RGBA 값 , HSLA 값을 사용하여 색상을 지정할 수도 있다.

```
<h1 style="background-color:rgb(255, 99, 71);">rgb(255, 99, 71)</h1>
<h1 style="background-color:#ff6347;">#ff6347</h1>
<h1 style="background-color:hsl(9, 100%, 64%,0.5);">hsl(9, 100%, 64%,0.5)</h1>
```

## css 배경 


```
body {
  background-color: #ffffff;
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
  background-position: right top;
}
```

<li>background-color - 요소의 배경 색상을 지정합니다.</li>
<li>background-image - 배경으로 사용하는 화상을 지정한다.</li>
<li>background-repeat - 이미지를 가로 및 세로로 반복합니다.</li>
<li>background-attachment- 배경 이미지를 스크롤해야하는지 아니면 고정해야하는지 여부를 지정합니다.</li>
<li>background-position - 배경의 위치를 정합니다.</li>
<li>background (약식 속성) - 코드를 줄이기 위해 하나의 단일 속성에 모든 배경 속성을 지정할 수도 있습니다.</li>
<li>opacity - 요소의 불투명도 / 투명도를 지정합니다. 0.0 - 1.0의 값을 사용할 수 있습니다. 값이 낮을수록 더 투명해집니다.</li>



## css 테두리

<li>dotted - 점선 테두리를 정의합니다.</li>
<li>dashed -파선 테두리를 정의</li>
<li>solid - 단색 테두리를 정의합니다.</li>
<li>double - 이중 테두리 정의</li>
<li>groove- 3D 홈 테두리를 정의. 효과는 테두리 색상 값에 따라 다릅니다.</li>
<li>ridge- 3D 융기된 테두리를 정의. 효과는 테두리 색상 값에 따라 다릅니다.</li>
<li>inset- 3D 삽입 테두리를 정의. 효과는 테두리 색상 값에 따라 다릅니다.</li>
<li>outset-3D 아웃 셋 테두리를 정의. 효과는 테두리 색상 값에 따라 다릅니다.</li>
<li>none - 경계를 정의하지 않음</li>
<li>hidden - 숨겨진 테두리를 정의합니다.</li>

## css 여백, 패딩

### css 여백

여백은 정의된 테두리 외부의 요소 주위에 공간을 만드는 데 사용된다.

<p><img src="https://velog.velcdn.com/images%2Fsanna422%2Fpost%2F7a884140-7c2b-4476-9231-42c7cef6a732%2Fimage.png" alt="요소 사진"></p>

CSS에는 요소의 각 측면에 대한 여백을 지정하는 속성이 있다.
<li>padding-top</li>
<li>padding-right</li>
<li>padding-bottom</li>
<li>padding-left</li>



모든 여백 속성은 다음 값을 가질 수 있습니다.
<li>auto-브라우저가 여백을 계산합니다.</li>
<li>길이 - 여백을 px, pt, cm 등으로 지정합니다.</li>
<li>% - 포함하는 요소 너비의 %로 여백을 지정합니다.</li>
<li>상속 - 여백이 부모 요소에서 상속되어야 함을 지정합니다.</li>

### css 패딩

패딩은 정의된 테두리 내부의 요소 콘텐츠 주위에 공간을 만드는 데 사용된다.

<p><img src="https://velog.velcdn.com/images%2Fsanna422%2Fpost%2Fd3386140-c9de-448f-a15a-23b51f63473a%2Fimage.png" alt="패딩 사진"></p>

<li>padding-top</li>
<li>padding-right</li>
<li>padding-bottom</li>
<li>padding-left</li>


모든 패딩 속성은 다음 값을 가질 수 있다</li>
<li>길이 - px, pt, cm 등으로 패딩을 지정합니다.</li>
<li>% - 포함하는 요소 너비의 %로 패딩을 지정합니다.</li>
<li>상속 - 패딩이 부모 요소에서 상속되어야 함을 지정합니다</li>
