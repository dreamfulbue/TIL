# TIL
오늘 내가 배운 것들(Today I Learned)

## 1일차 학습
- GitHub 계정 생성
- GitHub 저장소 생성
- GitKraken 설치
- GitKraken을 사용하여 GitHub 저장소 데이터를 내 컴퓨터로 복제(Clone)

구조 디자인(HTML)
[HTML 이란?]
- HTML (HyperText Markup Language)
- 확장자 : .html

[시멘틱 마크업]
- Semantic Markup
<h1></h1> - 제목 heading
<p></p> - 단락 paragraph

[기본 문법]
element : tag name / attribute name, value
<태그이름 속성="값">컨텐츠</태그이름>
<tag attr="value">contents</tag>

<p title="Development Tools">개발도구(DevTools)</p>
title속성 : 툴팁제공

<html>
  <head>
  <meta characterSet=""UTF-8">
    <title>HTML 문서 작성을 위한 기본 문법</title>
  </head>
  <body>
  </body>
</html>

- console창 > document.characterSet 입력 >  문자 인코딩 반환 (UTF-8).

[텅 빈 요소]
- meta : 내용컨텐츠를 감싸지 않아 닫는 태그가 필요 없음. (empty element)

[표준 호환모드]
html(root) : html 요소는 오직 1개의 head와 뒤 따르는 1개의 body 요소만 자식으로 포함

DTD : 문서 유형 정의(Document Type Definition)
<!DOCTYPE html> : 웹표준문서

[주 언어 설정]
<html lang="ko-KR">
ko/en/es/ja

**KR** Republic of Korea 지역(locale) 정보. ko 만 사용하면 한국어를 통칭
(참고) en-GB ⇒ 영국 영어 / en-US ⇒ 미국 영어 / en-CA ⇒ 캐나다 영어

[제목과 단락]
제목(Headings)
제목 레벨(Level) : 1~6단계
1단계는 문서에서 1번만 사용
2단계부터는 여러개의 제목을 사용할 수 있다.
<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
<h6></h6>
<!--주석-->
<p>단락</p>

[이미지와 피규어]
<img> image
figure / caption

<figure>
  <img src="" alt="대체 텍스트">
  <figcaption>이미지 출처 등 캡션</figcaption>
</figure>

figure : 이미지, 차트, 도표 등을 감싸는 태그
alt(alternative) : 대체텍스트, 이미지를 분석하여 묘사할것.


[문법 검사]
validator.w3.org : 문법 유효성 검사
entitycode.com
&lt; &gt; &copy; &midot; &nbsp; &amp;

[순차/비순차 목록]
ul : unordered lists 비순차 목록
ol : ordered lists 순차 목록
li : list Item
