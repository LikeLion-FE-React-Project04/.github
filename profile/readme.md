<!-- ![header](https://capsule-render.vercel.app/api?text=Market%20Karly&fontAlign=70&=Desc&descAlign=20) -->
![header](https://capsule-render.vercel.app/api?type=waving&color=0:5F0080,100:FFFFFF)
<!-- # <div align="center">🦁 LikeLion 프론트엔드 스쿨 4기 FINAL PROJECT 🦁</div> -->
<!-- ![image](https://user-images.githubusercontent.com/112063987/233653395-53c97abc-dd18-4de2-888e-88d7cbe95384.png) -->
<!-- ![image](https://user-images.githubusercontent.com/112063987/233664236-192af5b5-3f49-435e-a65c-c4af44a05aeb.png) -->

<div align="center"><img src="https://user-images.githubusercontent.com/112063987/233669862-47a68263-8187-465d-bcd5-c3c94568818a.png" width="400"></div>

## 프로젝트 소개
> 멋쟁이사자처럼 프론트엔드 스쿨 4기 4조의 FINAL PROJECT로 진행한 Karly(칼리) 입니다. <br />
> 실제 온라인 쇼핑몰인 컬리(Kurly)를 참고하였습니다.

## 개발 기간
> 프로젝트 기간: 2023.03.09 ~ 2023.03.28 (모든 팀원 참여)<br/>
> 추가 작업 기간: 2023.03.29 ~ 2023.04.14 (김종엽,서미영,서석원 참여)

## 팀원(Contributors)
<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/kelly121212">
          <img src="https://github.com/kelly121212.png" width="100">
        </a>
      <td align="center">
        <a href="https://github.com/ssw6750">
          <img src="https://github.com/ssw6750.png" width="100">
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/SeoMiYoung">
          <img src="https://github.com/SeoMiYoung.png" width="100">
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/PracticeKJY">
          <img src="https://github.com/PracticeKJY.png" width="100">
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/tkdkfkgk">
          <img src="https://github.com/tkdkfkgk.png" width="100">
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">최보영</td>
      <td align="center">서석원</td>
      <td align="center">서미영</td>
      <td align="center">김종엽</td>
      <td align="center">문진기</td>
    </tr>
  </tbody>
</table>

<details>
    <summary>목차</summary>
    <div markdown="1">1. 역할 분담</div>   
    <div markdown="2">2. 기술 스택</div>  
</details>


## 1. 역할 분담 :speaking_head: 
#### :loudspeaker: src/pages 
- Sprint1: ```Home(메인 페이지)``` / ```SingIn(로그인 페이지)``` / ```SignUp(회원가입 페이지)```
- Sprint2: ```ProductDetail(제품 상세 페이지)``` / ```ProductList(제품 나열 페이지)``` / ```Cart(장바구니 페이지)```
> 저희조는 작업을 Sprint1과 Sprint2로 나눈 뒤, Sprint1작업이 모두 끝난 후, Sprint2로 들어갔습니다.<br />
> 각 Sprint마다 각자 역할을 맡아서 진행했습니다.

#### :loudspeaker: src/components
> 저희조는 처음에 공용 컴포넌트들을 먼저 파악하고 시작하려고 노력했습니다. <br/> 
> 공용컴포넌트들은 components 폴더안에 모아두었습니다. <br/>

#### :white_check_mark: 최보영(조장)
#### :white_check_mark: 서석원(스크럼마스터)
  - 프로젝트 초기 세팅(해당 카테고리 참고): 웹팩 빌드툴 개발 / 라우팅 세팅 / 스토리북 연결
  - ```Home```: 메인 캐로셀 / 상품 캐로셀 / 공용 상품 카드 / 장바구니 모달(CartModal) / 공용 카운터 컴포넌트(Counter)
  - ```SignUp```: 컴포넌트 분리 / 유효성 검사 (정규 표현식) / 약관동의 / 주소 검색 (공용 커스텀 훅) / 이메일 중복 검사 (파이어베이스) / 회원가입 (파이어베이스)
  - ```ProductDetail```: 네비게이션 구현
  - ```Cart```: 공용 아코디언 컴포넌트(Accordion) / 상품 아코디언 구현 / 주소 검색 / 상품 금액 계산 로직 구현
  - 다크 필터 컴포넌트(DarkFilter)
#### :white_check_mark: 서미영
  - ```Home```: 메인 모달창(MainModal), 라인베너(LineBanner) 구현
  - ```Common(모든페이지)```: 푸터(Footer)
  - ```ProductDetail```: 상품문의 구현 / 공용 후기&문의작성 팝업창 컴포넌트(ProductDetailPopUp) / 공용 Badge 컴포넌트(Badge) / 후기&문의작성에 대한 데이터를 파이어스토어에 넣고 가져오는 공용 커스텀 훅 구현(파이어베이스)
  - 경고창 컴포넌트(AlertBox), 투명 필터 컴포넌트(TransparentFilter), 스크롤 이동 컴포넌트(ScrollToTop)
#### :white_check_mark: 김종엽
#### :white_check_mark: 문진기

## 2. 기술 스택 :gear: 
<!--
<img src="https://img.shields.io/badge/텍스트-컬러코드?style=for-the-badge&logo=아이콘이름&logoColor=white"/>
-->
<div>
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/cssmodules-000000?style=for-the-badge&logo=cssmodules&logoColor=white"/>
<br />
<img src="https://img.shields.io/badge/webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=white"/>
<img src="https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white"/>
<img src="https://img.shields.io/badge/babel-F9DC3E?style=for-the-badge&logo=babel&logoColor=white"/>
<img src="https://img.shields.io/badge/eslint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white"/>
<img src="https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=Prettier&logoColor=white"/>
<br />
<img src="https://img.shields.io/badge/recoil-f26b00?style=for-the-badge&logo=relay&logoColor=white"/>
<img src="https://img.shields.io/badge/reactrouter-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white"/>
<img src="https://img.shields.io/badge/storybook-FF4785?style=for-the-badge&logo=storybook&logoColor=white"/>
<img src="https://img.shields.io/badge/firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white"/>
<img src="https://img.shields.io/badge/netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white"/>
</div>



## 3. Cowork Tools 🦁 
<div>
<img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"/>
<img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white"/>
<img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
<img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/visualstudiocode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
</div> 

## 4. 프로젝트 초기 세팅 :hammer: 
<details>
<summary>:white_check_mark: 빌드툴 관리 - Webpack 기본 설정</summary>

![image](https://user-images.githubusercontent.com/112063987/233780244-008b952c-97fe-41f3-ac3e-3c09f050d1ee.png)
</details>
<details>
<summary>:white_check_mark: 빌드툴 관리 - Webpack 빌드 및 분석</summary>

![image](https://user-images.githubusercontent.com/112063987/233780407-d826ab4f-12bd-484f-b5a1-fd6cd3265c24.png)
</details>
<details>
<summary>:white_check_mark: 패키지, 폴더</summary>

![image](https://user-images.githubusercontent.com/112063987/233780660-d83a1141-c316-43b1-a7e5-035569ad84d2.png)
</details>
<details>
<summary>:white_check_mark: 라우팅, 테스팅</summary>

![image](https://user-images.githubusercontent.com/112063987/233780716-bc4e58b3-ac66-40e6-be24-bc04620c7ace.png)
</details>

## 5. 컨벤션 :bookmark_tabs: 
<details>
  <summary>:white_check_mark: Gitmoji</summary>
  <table>
  <thead>
    <tr>
      <th align="center">Emoji</th>
      <th align="center">Text</th>
      <th align="center">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">✨</td>
      <td align="center">[feat]</td>
      <td align="center">새롭게 만드는 코드(html,css,javascript 등 모두)</td>
    </tr>
    <tr>
      <td align="center">🎨</td>
      <td align="center">[modify]</td>
      <td align="center">기존 코드 수정</td>
    </tr>
    <tr>
      <td align="center">⚡️</td>
      <td align="center">[refactoring]</td>
      <td align="center">리팩토링</td>
    </tr>
    <tr>
      <td align="center">🐛</td>
      <td align="center">[fix]</td>
      <td align="center">버그 문제 수정</td>
    </tr>
    <tr>
      <td align="center">✅</td>
      <td align="center">[test]</td>
      <td align="center">테스트</td>
    </tr>
    <tr>
      <td align="center">💄</td>
      <td align="center">[style]</td>
      <td align="center">CSS수정</td>
    </tr>
    <tr>
      <td align="center">🔧</td>
      <td align="center">[setting]</td>
      <td align="center">환경 설정</td>
    </tr>
    <tr>
      <td align="center">📝</td>
      <td align="center">[docs]</td>
      <td align="center">readme.md 등의 문서 수정</td>
    </tr>
  </tbody>
</table>
</details>

<details>
  <summary>:white_check_mark: Commit 컨벤션</summary>
  - Gitmoji 확장프로그램 설치 후 사용<br />
  - Gitmoji 카테고리에 해당되는 분류 클릭 후, [ 소문자 ] + 이슈내용 + #이슈번호<br />
  <img src="https://user-images.githubusercontent.com/112063987/233770199-be4785ea-1f46-4e53-844f-1b9474f6a4ad.png" width="350">
</details>

<details>
  <summary>:white_check_mark: 네이밍 컨벤션</summary>
  - 이름을 통해 쓰임새를 알 수 있도록 한다. (20자 미만, 직관적으로)<br />
  - 이름의 맨 앞이나 맨 뒤에 언더바(_)를 사용하지 않는다.<br />
  <table>
    <tr>
      <td align="center">image, svg</td>
      <td>단어 사이 -를 사용해 네이밍(ex. erase-check.svg)</td>
    </tr>
    <tr>
      <td align="center">이벤트 핸들러</td>
      <td>on + 메소드명 + Handler</td>
    </tr>
    <tr>
      <td align="center">변수, 함수, 인스턴스</td>
      <td>Camel Case(카멜 케이스)</td>
    </tr>
    <tr>
      <td align="center">함수 이름</td>
      <td>'동사+명사' 구조로 네이밍(ex. makingItem(x) / makeItem, getItem, changeItem (o))</td>
    </tr>
    <tr>
      <td align="center">Class, Constructor</td>
      <td>Camel Case(카멜 케이스)</td>
    </tr>
    <tr>
      <td align="center">상수</td>
      <td>Scream Snake Case (스크림 스네이크 케이스)</td>
    </tr>
  </table>
</details>

<details>
  <summary>:white_check_mark: 코드 컨벤션</summary>
  <table>
    <tr>
      <td align="center">Tab Depth<br/>(들여쓰기)</td>
      <td>
        기본 tab depth: 4 (유동적으로)
        <br />
        <img src="https://user-images.githubusercontent.com/112063987/233770688-c4c1c6b0-1eb7-4a2f-8229-de419c19e1bd.png" width="250">
      </td>
    </tr>
    <tr>
      <td align="center">Comment<br/>(주석)</td>
      <td>
        1) // : 기본 주석입니다. <br />
        2) //? : 의견을 묻는 주석 예시입니다. → 의견을 구해야하거나, 피드백을 구하려할때 사용해주세요. <br />
        3) //! : 주의해주세요 → 신경쓸 부분이나 중요한 이야기가 있을 때 사용해주세요. <br />
        4) 분류 주석 : 분류가 될만한 부분은 줄 주석으로 나눠주세요. (다음 확장 프로그램을 설치해주세요) <br />
        &nbsp;&nbsp;&nbsp;&nbsp;- 확장프로그램: https://marketplace.visualstudio.com/items?itemName=stackbreak.comment-divider<br />&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://user-images.githubusercontent.com/112063987/233770939-995b52c9-be62-49ec-80a4-cc24555a8649.png" width="450">
      </td>
    </tr>
  </table>
</details>

      
## 6. git branch 전략 :busts_in_silhouette: 
저희팀은 git branch 전략으로, git flow 방식을 선택했습니다.
> main : 기준이 되는 branch로 제품을 배포하는 브랜치 입니다.<br />
> develop : 개발 branch로 개발자들이 이 브랜치를 기준으로 각자 작업한 기능들을 합(Merge)칩니다.<br />
> feature : 단위 기능을 개발하는 branch로 기능 개발이 완료되면 develop branch에 합(Merge)칩니다. <br />

#### :loudspeaker: feature branch 컨벤션
단위 기능을 개발하는 branch인 feature branch의 경우, 다음과 같은 형식으로 네이밍합니다.
```
feat/#이슈번호
```

## 7. 디렉터리 구조 :open_file_folder: 

## 8. 페이지별 기능 소개 :sparkles:  
## 9. 프로젝트 사용법 :question: 
다음 순서대로 명령어를 입력해주세요.
```
npm install -g pnpm
pnpm install
npm start
```
## 10. 배포 링크 :tada: 


![footer](https://capsule-render.vercel.app/api?section=footer&type=waving&color=0:FFFFFF,100:5F0080)
