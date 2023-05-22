##<!DOCTYPE html> 웹문서의 유형을 html 로 지정

<html> 모든 html 태그들의 최상위 태그
    <head> 문서의 공통적인 특성을 넣는 곳 
        <meta> 메타 데이터 입력
    
        <title> 문서의 제목
        
    </head>
    
    
    <body> 문서의 본문, 여기에 내용을 나타냄
 </html>
       
    

##제목 
1. <h1> 제목1 </h3>
2. <h2> 제목2 </h3> 


##문단
1. <p> 문단 글 쓰기 등등 </p>
2. <p> 문단 글 쓰기 2 등등 </p>

##줄바꿈
1. <p> 첫번째 글 1 <br>
    두번째 글 2 <br>
    세번쨰 글 3 <br>
  </p>

##문단 나누기
1. <p> 문단 나누기 </p>
   <hr>
   <p> 나눠진 문단 </p>


#텍스트 효과

##굵게 b(bold)

1. <p> 동해물과 백두산이 <b class="tern"> 마르고 닳도록</b> 하느님이 보우하사
    우리나라 만세. 남산 위에 <b class="tern"> 저 소나무 </b>철갑을 두른듯
  </p>

##기울임 i(idiomatic)

1. <p> <i>동해물과 백두산이 마르고 닳도록</i> 하느님이 보우하사
    우리나라 만세. <i> 남산 위에 저 소나무 철갑을 두른듯 </i> 바람서리
   </p>

##밑줄 u(underline)

1. <p> 동해물과 <u>백두산이 마르고 닳도록</u> 하느님이 보우하사
    <u>우리나라 만세</u>. 남산 위에 저 소나무 철갑을 두른듯 바람서리
  </p>

u태그를 사용하기 보다 css의 text-decoration 속성을 underline 으로 지정하는것이 좋다

취소선 s(strikethrough)

<p> 동해물과 백두산이 마르고 닳도록 하느님이 보우하사
    우리나라 만세. <s>남산 위에 저 소나무 철갑을 두른듯 바람서리</s>
</p>



문서 구조 태그

<header>	헤더 영역
<main>	메인 영역
<section>	콘텐츠 영역
<aside>	사이드 바 영역
<footer>	푸터 영역

<nav> 내비게이션 영역, 문서 내 다른 위치, 다른 문서로 연결할 때 사용
<article> 독립적인 콘텐츠를 사용할 때
<section> 콘텐츠 영역
<div> 여러 소스 묶기
<figure> vd




목록 입력

  <ol>
    <li>목록 1</li>
    <li>목록 2</li>
  </ol>
  
  <hr>
  
  type에는 "1", "a", "A", "i", "I"를 넣을 수 있다.
  
  <ol type="a">
    <li>목록 1</li>
    <li>목록 2</li>
  </ol>
  
  <hr>
  
  특정 숫자부터 시작하게 할 수 있다.
  
  <ol start="3">
    <li>목록 1</li>
    <li>목록 2</li>
  </ol>


  
이미지 삽입

<img src="이미지 파일 경로" alt="대체용 텍스트">

이미지 사이즈 변경 <img width="10px" height="5px"> </img>

오디오, 비디오 등 멀티미디어 파일 삽입

<object> 기본형
    오디오, 비디오, PDF 등을 삽입할 때 사용한다.

<object width="너비" height="높이" data="파일"> </object>

<embed> 기본형 - 닫기 태그 없음
    오디오, 비디오, 이미지 등

<embed src="파일경로" width="너비" height="높이"

플러그인 필요없이 브라우저에서 바로 재생하는 태그 (html 5부터)

<audio src="오디오 파일 경로"> </audio>

<video> 기본형

<video src="비디오 파일 경로"></video>

<video> <audio> 태그 속성
    controls= 컨드롤 바 표시
    autoplay= 자동 재생
    loop= 반복 재생
    muted= 음소거
    preload= 로딩 방법, 사용할 수 있는 값은 auto(기본값), metadata, nav-item-button-active
    width=, height= 비디오 플레이어의 너비, 높이 지정
    poster= "파일이름"  비디오 플레이어의 재생 전 포스터


하이퍼링크 삽입
기본형 
<a href="링크할 주소">텍스트 또는 이미지</a>
href= 링크 주소 
target= "_blank" 새 탭에서 열기 (기본값은 현재 페이지에서 열기)

텍스트 링크 예시) <p><a href="~">표시 텍스트 </a></p>
이미지 링크 예시) </a><img src="이미지 파일 경로" alt></a>


<input>의 속성 값들

type= 
{
    text	한 줄 텍스트
    password	비밀번호
    search	검색
    url	url
    email	이메일 주소
    tel	전화번호
    checkbox	체크박스 (중복 체크)
    radio	라디오 버튼 (unique 체크)
    number	숫자 스핀 박스(버튼으로 숫자 조절)
    range	숫자 슬라이드 막대
    date	local - 연, 월, 일
    month	local - 연, 월
    week	local - 연, 주
    time	local - 시, 분, 초, 분할 초
    datetime	UTC - 연, 월, 일, 시, 분, 초, 분할 초
    datetime-local	local - 연, 월, 일, 시, 분, 초, 분할 초
    submit	전송 버튼
    reset	리셋 버튼
    image	submit 버튼 이미지
    button	일반 버튼
    file	파일 첨부 버튼
    hidden	사용자에게 보이지 않는 값 필드
}


text, password와 같이 쓰이는 속성들
{
    size=	화면에 출력할 글자 수
    value=	text 필드에 보여줄 내용,password에서 사용 안함
    maxlength=	최대 입력 가능한 글자 수

}


checkbox, radio와 같이 쓰이는 속성들
{
    value=	서버에 전달될 값
    checked=	기본으로 선택하고 싶은 항목 name=	radio 전용,여러 옵션의 공통 이름
}


numver, range와 같이 쓰이는 속성들
{
    min=	최소값(기본값 0)
    max=	최대값(기본값 100)
    step=	조정할 단위값(기본값 1)
    value=	초기값
}

submit, reset와 같이 쓰이는 속성들(이 속성들은 버튼이다)
{
    value=	버튼에 표시할 내용
}


image와 같이 쓰이는 속성들
{
    src=	이미지 경로
    alt=	대체 텍스트
}

button와 같이 쓰이는 속성들  참고 - (https://hianna.tistory.com/677)
{
    value=	버튼에 표시할 내용
    onclick=	클릭 시 실행할 JS함수
}

