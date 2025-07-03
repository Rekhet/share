---
title: "Design Requests"
date: "2025-07-01"
---

# Primary Requests

Target | Styles | Sizes | Arrangements | Colors | Images
--- | --- | --- | --- | --- | ---
Text | $$\blacksquare$$ | $$\blacksquare$$ | $$\blacksquare$$ | $$\blacksquare$$ | $$\square$$
Object | $$\blacksquare$$ | $$\blacksquare$$ | $$\blacksquare$$ | $$\blacksquare$$ | $$\square$$
Background | $$\blacksquare$$ | $$\square$$ | $$\square$$ | $$\blacksquare$$ | $$\blacksquare$$

## To be designed

<page style="font-size:18px">
Header <br>
Footer <br>
Homepage <br>
Login <br>
SCSC <br>
Peoples <br>
Rules <br>
Board-Type1 <br>
Board-Type2 <br>
Contact <br>
</page>
<br>

# Page Structure

```mermaid
flowchart TD
    A[Homepage] --> B[About us]
    A ----> C[Board]
    A ------> D[SIG/PIG]
    A --------> E[Contact]
    B --> F(SCSC)
    B --> G(Executives)
    B --> H(Developers)
    B --> I(Rules)
    
    C --> J(Project Archives)
    C --> K(Album)
    C --> L(Notice)
    
    D --> M(SIG)
    D --> N(PIG)
    
    E --> O(Contact Us!)
    E --> P(Join Us!)

    Q[Login]
```

<br><br>

<video controls src="temp_1751470917284.1414414502.mp4" title="Title"></video>


## Overall

Requests : <br>
배경색에 대한 변경 제안이 있을 시 부탁 <br>
글씨체 개선 (가능한 한 컴퓨터동아리라는 특징이 부각될 수 있도록) <br>
위 영상을 참고하여, 페이지별 동작 이벤트들에 대한 개선 제안이 있을 시 포함 부탁. <br>
페이지 컴포넌트로 구현이 되어 있지 않으나 있으면 좋을 만한 것들에 대한 의견도 있다면 부탁. 페이지 갈아 엎는 것도 환영.

---

## Headers & Footers

### Header Composition: 

![alt text](image-8.png)

- Logo <br><br>
  <img src="image-7.png" width="200px"></img> <br><br>
- About us
- Board
- SIG/PIG
- Contact
- 로그인

Functions : <br>
1. 메뉴 위 마우스 호버 이벤트(특정 오브젝트 위에 마우스를 올려 놓을 시 발생하는 변화): 토글<br>
![alt text](image-10.png)
  

Notes : `None`

Requests : <br>
Header size 및 버튼 배치에 변경 <br>
사진과 같이 세부 사항을 확인할 때 뜨는 창에서 호버 이벤트 속 색 <br>


### Footer Composition: 

![alt text](image-9.png)

- 대표자(회장) 연락처
- 동아리 공식 계정(EMail, GitHub, Instagram)

Functions : `None`

Notes : `None`

Requests : <br>


## Homepage
![alt text](image.png)

Functions : 
로딩 시 "//Welcome to SCSC" 문구가 입력된 후 커서가 깜빡이는 상태 유지 <br>
<video src="HomepageText.mp4" controls width="600"></video>


Notes : <br>
Fireart 메인 페이지와 유사하게 배경에  <br>
단일 페이지

References : [Fireart](https://fireart.studio/)

Requests : `None`


## Login

![alt text](image-6.png)

Functions : 현재 구현된 것이 거의 없는 상태

Notes : 현재 Google을 통해 계정을 관리하나, 로그인 페이지에 저 버튼이 하나 뿐인 것이므로 시각적으로 허전

References : [Muzli](https://muz.li/)

Requests : <br>
SCSC 로고 등의 이미지 및 로그인 버튼 오브젝트를 포함한 로그인 페이지 구성 (위 Reference) 

![Muzli의 로그인 창](image-12.png)
(Muzli의 로그인 창)

위 이미지 참고 요망 <br>
각각의 요소들에 대한 글씨체 설정

## MyPage 

Notes : <br>
<br>
포함 요소
- 이메일
- 이름
- 전화번호
- 학번
- 전공 <br>
현재는 배치가 되어 있지 않은 상태이며, 추후 다른 인적사항 항목이 추가될 수도 있음.


References : [Examples](https://fireart.studio/blog/how-to-design-best-profile-page-top-15-examples/)

Requests : <br>
개인인적사항이 작성되어 있는 페이지를 제작



---
## About us

### SCSC

![alt text](image-1.png)

Functions : <br>
스크롤에 따라 페이드인으로 아래의 요소들이 표시되기 시작함 <br>
'동아리방에는 무엇이 있을까요?'에서 각각의 사진 포함 박스에 마우스 호버 시 미세 이동을 통한 입체적 효과 있음 <br>
'SCSC에 대해 더 알아보고 싶다면?' 아래에 링크들 연결 <br>
FAQ에서 토글 존재

Notes : <br>
현재는 그저 텍스트 박스들에 의해 정리가 되어 있으며, 일직선으로 모든 오브젝트 배치되어 있는 상태.

References : [Apple](https://www.apple.com/store), [Dropbox](https://www.dropbox.com/dropbox), [Muzli](https://muz.li/)

Requests : <br>
현재 배치되어 있는 오브젝트들을 청크화한 후 재배치 <br>
글자 스타일 & 사이즈 변경 <br>

### Executives

![alt text](image-2.png)

Functions : <br>
각 박스에 대한 호버 이벤트 (영상 참고)

Notes : <br>
Developers 페이지와 사실상 동일

References : [Apple](https://www.apple.com/store)

Requests : <br>
박스 배치 및 페이지 구성에 대한 개선 (예: Apple 페이지의 프로덕트 표시처럼 가로 스크롤로 배치, 박스 형태 변경 등) <br>
활용되는 글씨체 개선 제안

### Developers

![alt text](image-3.png)

Notes : Executives 페이지와 동일

### Rules

![alt text](image-4.png)

Functions : None

Notes : <br>
회칙이 그냥 단순 텍스트 박스 안에 포함되어 있으며, 가운데에 오브젝트로 존재. 해당 오브젝트 외의 페이지가 비어 있어 미완성 또는 미흡의 느낌을 줌.

References : [민법](https://law.go.kr/lsSc.do?section=&menuId=1&subMenuId=15&tabMenuId=81&eventGubun=060101&query=%EB%AF%BC%EB%B2%95#AJAX), [Apple Privacy Policy](https://www.apple.com/legal/privacy/en-ww/), [AirBnB Terms of Service](https://www.airbnb.com/help/article/2908?locale=en&_set_bev_on_new_domain=1751474724_EAOTVkNWE0YjJjYz), [Dropbox Terms of Service](https://www.dropbox.com/en/terms)

Requests : <br>
민법 페이지의 조항 링크 구조를 참고하며, Apple Privacy Policy(드롭다운 형식) 또는 AirBnB Terms of Service(장문 형식) 및 기타 페이지들 중 선택하여 유사한 양식으로 구성 (전반적으로 약관, 규정 페이지들 양식이라고 생각하면 됨.)

## Board

Function : <br>
- 글 작성 <br>
- 게시글 열람

Notes : <br>
글의 영역과 배경의 영역 구분이 없으며, 영역 사이즈로 인한 공백이 생겨 허전함을 주는 문제가 있으나, 그렇다고 이 영역을 무작정 늘리는 것은 불가능함.

Requests : <br>
게시판
게시글 열람 - 제목, 글 정보, 글 내용을 포함한 텍스트 뷰어 영역을 만들고, 배경과 구분을 지어 빈 페이지 느낌을 줄이기 <br>
(희망사항) 배경 페이지를 디자인/이미지 등 추가를 통해 어느 정도 채워진 느낌이 들 수 있도록 만들기 <br>
(희망사항) 글 작성 페이지 (영상 3:30 참조) 텍스트 에디터 영역 또한 같은 사항 적용

### Project Archives

Notes : 기본 구조가 동일하므로 같은 내용 적용

### Album

Notes : 기본 구조가 동일하므로 같은 내용 적용

### Notice
 
Notes : 기본 구조가 동일하므로 같은 내용 적용

## SIG/PIG

Notes : 기본 구조가 동일하므로 같은 내용 적용

### SIG

Notes : 기본 구조가 동일하므로 같은 내용 적용

### PIG

Notes : 기본 구조가 동일하므로 같은 내용 적용

## Contact

### Contact Us!

![alt text](image-5.png)

Functions :

Notes :

Requests : 

### Join Us!

![alt text](image-6.png)

Functions : `None`

Notes : Not implemented yet.

Requests : 