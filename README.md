# naver-ordering-page
네이버 주문 페이지 클론코딩
퍼블리싱 연습을 위한 레포입니다.



### 폴더 구조
```
├── assets
│   ├── css
│   │   ├── styles.css  // 컴파일 출력 결과
│   │   ├── styles.css.map  // 
│   │
│   ├── images
│   └── scss
│       ├── abstracts   // mixin, 사전에 선언한 값들
│       ├── base        // reset, preset
│       ├── components  // 컴포넌트 요소
│       ├── pages       // 특정 페이지 scss
│       ├── styles.scss // 모든 scss파일 import. 컴파일 대상
│
├── docs
│   ├──index.html
│
└── node_modules
```



### 개발 환경 설정
```
npm i
sudo npm i -g sass
```

VScode의 Extension에서 Live Server설치, Live Sass Compiler 설치



#### Live Sass Compiler
(사진)
위 사진과 같이 **setting.json에서 편집**을 누른 후 setting.json 파일을
(사진)
과 같이 바꿔줍니다. "savePath"의 경우 컴파일 된 .scss파일이 .css로 출력될 디렉토리입니다.

개발 할 땐 VScode 하단의 **Watch Sass** 버튼을 눌러 변경사항이 있을 시 바로 적용될 수 있게 합니다.


#### Live Server
Windows: Alt + L + O
MAC: Command + L + O
