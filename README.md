# 프론트엔드 기초 수업 
> [Github저장소](
https://github.com/ministori-yonsei/green_weekend_03)    
> [CodePen 저장소](https://codepen.io/ministori-yonsei)
## GITHUB 기초 개념 

  > GITHUB 용어 Cancel changes
- stage : commit 할 대상을 선택.
- commit : 수정한 내용의 스냅샷을 찍음.
- push : GITHUB 서버에 업로드
- pull : GITHUB 서버에서 다운로드 
- branch : 각각의 개발자가 독립적으로 개발하기 위한 한 가지 
- pull request : 각각의 branch 에서 개발한 것을 master branch로 병합하기 위한 요청   
- merge : 각각의 branch 에서 개발한 것을 master branch로 병합하는 것 


  > 사이트 링크
 마크다운 사용법 : [안내문서](https://github.com/baejihyeon/green_weekend_03/edit/main/README.md)<br/> 
 HTML, CSS, JS 참고 사이트 : [W3Schools](https://www.w3schools.com/css/default.asp)<br/>
 온라인 에디터 :[Codepen](https://codepen.io/trending)
 
 
 ## WEB IT 기초 개념 
 
 > 클라이언트 서버 모델 
 <img src = "https://github.com/baejihyeon/green_weekend_03/blob/main/dd.png" width = "648"/>
 
 클라이언트 - 서버 모델에서 클라이언트는 사용자가 사용하는 디바이스 (PC,Mobile)를 의미하고, 서버는 클라이언트가 접속해서 데이터나 파일을 요청했을때 응답하는 시스템 
클라이언트와 서버는 네트워크를 통해서 연결됌 

 <img src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDI2xXw64XnKf7xamh-8-Lr6cZ3Dfo784JTA&usqp=CAU" width = "648"/>
 클라이언트와 서버모델은 실제 연결은 아니지만 개념적으로 클라이언트 관점에서 1:1로 연결되었다고 생각할 수 있음 
 클라이언트 서버 모델에서 이루어지는 동작은 클라이언트의 요청(request)과 응답(response)의 1 사이클로 구성됨 
 클라이언트는 클라이언트 디바이스에서 실행되는 웹브라우저, 서버는 서버 디바이스에서 실행되는 서버 소프트웨어거 실제로 사용되는 것임

## HTML 
> [HTML Introduction](https://www.w3schools.com/html/html_intro.asp)<br/>
> [HTML Attribute](https://www.w3schools.com/html/html_attributes.asp)<br/>   
> [HTML Element](https://www.w3schools.com/html/html_elements.asp)<br/>

## HTML 속성(Attributes)
   1) HTML Element에 추가 정보를 제공
   2) name = "value" 형태로 사용

 웹 문서에서 표시할 수 있는 콘텐츠 
   1) 텍스트
   2) 이미지
   3) 멀티미디어(비디오,오디오)
  
 
 
### 텍스트 콘첸츠 요소(Element) 


>[HTML Headings](https://www.w3schools.com/html/html_headings.asp)<br/>


제목태그(Tag)
Heading -> h 
h1 ~ h6

>[HTML Paragraphs](https://www.w3schools.com/html/html_paragraphs.asp)<br/>

단락 태그
Paragraph -> p

수평선 
Horizontal Rules -> hr(Empty Element)

>[HTML Links](https://www.w3schools.com/html/html_links.asp)


하이퍼링크
Anchor -> a
href : 링크로 연결된 목적지 주소 

1) 외부링크
 -  링크 주소 입력 시 http(https) 키워드를 사용

3) 북마크
 - 목적지에 id attribute를 사용해서 이름을 정해줌
 - href attribute애 #을 사용해서 목적지 이름을 입력

>[HTML Tables](https://www.w3schools.com/html/html_tables.asp)

 - [Table Generator](https://www.tablesgenerator.com/)

>[HTML Lists](https://www.w3schools.com/html/html_lists.asp)

1) 순서없는 목록(ul)
2) 순서있는 목록(ol)
3) 설명 목록

ul, ol 목록에서 중첩(nested) 형태로 사용할때 포함 관계를 주의
  - 포함하는 목록 항목에 작은 목록 전체가 포함됨

### 이미지 콘텐츠 요소 
[HTML Images](https://www.w3schools.com/html/html_images.asp)

1) src attribute :  가져올 이미지 파일 위치 정보
2) alt (alternative) attribute : 대체 텍스트 

### 멀티미디어 콘첸츠 요소 
[HTML](https://www.w3schools.com/html/html5_video.asp)

attribute 의 형태   
1)name = "value"     
2)name 만 사용    
  
video 태그의 attribute    
1) controls
2) autoplay
3) muted
4) loop 

[HTML YouTube Videos](https://www.w3schools.com/html/html_youtube.asp)
Youtube의 매개변수 
1) controls => youtube_url/VIDEO_ID?controls=1
2) autoplay =>youtube_url/VIDEO_ID?autoplay=1
3) muted =>youtube_url/VIDEO_ID?mute=1
4) loop =>youtube_url/VIDEO_ID?loop=1&playlist=VIDEO_ID

여러 매개변수 동시 사용 
youtube_url/VIDEO_ID?controls=1&autoplay=1&mute=1&loop=1&playlist=VIDEO_ID (& : ampersand)


### 프론트엔드 기술(HTML, CSS, JS)의 라우저 지원 여부 체크

- 프론트엔드 기술이 버전업 도리때마다 브라우저가 지원하는지 체크할 필요가 있음.
- HTML5/5.1 , CSS3, ES2015 버전들의 기술은 항상 지원여부 체크가 필요함.
- 브라우저 지원 여부
  - 상위 호환성 : 새 버전 브라우저의 지원 여부 
  - 하위 호환성 : 구 버전 브라우저의 지원 여부 
- 일반적으로 브라우저 지원은 하위호환성 체크가 중요함

- [CAN I USE](https://caniuse.com/)   

> [HTML Block and Inline Elements](https://www.w3schools.com/html/html_blocks.asp)   

- Non-semantic element(grouping 요소)
  - div(division)
  - span


### Block/Inline Element 

- block : 새 줄(줄바꿈)에서 표시
- inline : 한 줄에 나란히 표시 
- 포함관계
  - block : block, inline, contents(text) 모두 포함할 수 있음
  - inline : inline, contents(text)만 포함 가능 
