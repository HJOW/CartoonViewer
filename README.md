CartoonViewer
=============
# 이 프로그램은
이미지로 배포하는 만화를 PC에서 열면,
이미지의 세로 길이가 너무 길어, 확대 후 스크롤해가며 어렵게 보고 계시지 않습니까?

이 CartoonViewer 프로젝트는 이 문제를 해결합니다.
설치 없이, 웹 브라우저만으로 실행할 수 있으며, 파일 하나로 모든 동작이 가능합니다.

# 프로그램 사용을 위한 준비
자동 추가 도구를 이용하기 위해서는 이미지 파일들의 이름을 변경해 두어야 합니다.
확장자(jpg, png, ...)는 모두 동일하게 맞추어 주시고, 숫자를 제외한 부분을 똑같이 맞춰 주세요.

예:

* 재미있는 만화 001.png
* 재미있는 만화 002.png
* 재미있는 만화 003.png
* ...
* 재미있는 만화 021.png

이미지 파일들을 폴더 하나에 모두 담아 주세요.
그리고 CartoonViewer 동작 파일인 viewer.html 파일을 이 폴더 안에 같이 넣어 주세요.

이제 사용 준비가 되었습니다.

# 프로그램 사용 방법

viewer.html 을 웹 브라우저 (Microsoft Edge, Google Chrome, Mozilla Firefox ...) 로 실행해 주세요.

(주의 : Internet Explorer 9 이상 버전도 호환은 될 테지만 보장하지는 않습니다. 모바일 기기 또한 보장하지 않습니다.)

실행하면, 화면 상단에 있는 "도구" 영역 에서 이미지들을 추가할 수 있습니다.
이 "도구" 영역은 숨길 수 있습니다. 간단히 화면 상단 "도구" 글자를 클릭하면 숨겨지고, 또 클릭하면 다시 나타납니다.

## 자동 추가 도구

자동 추가 도구를 이용해 봅시다.
"동작", "파일 이름 규칙", "숫자 범위" 항목을 지정하게 되어 있습니다.
파일 이름 규칙에는 파일 이름을 적어 주세요. 단, 숫자가 들어갈 위치에 대괄호([]) 와 0을 자리수만큼 적어 주세요.

예: 재미있는 만화 [000].png

숫자 범위에는 파일 이름의 숫자 범위를 지정해 주세요.

예: 1 ~ 21

이제 우측의 "적용" 버튼을 클릭해 주세요.
화면 중앙에 이미지들이 순서대로 불러와 배치됩니다.

## 백업 / 복원

이 번거로운 작업들을 여러 번 하지 않아도 됩니다.
JSON 텍스트가 자동으로 생성되는데, 이 텍스트 내용을 복사해 파일로 저장해 두세요.
다음번에 만화를 다시 보고 싶을 때, 위의 번거로운 작업을 건너뛰고, 저장해둔 파일을 열어 텍스트를 복사한 다음
JSON 텍스트 란에 붙여넣고 "JSON 변경사항 적용" 을 클릭하시면 됩니다.

## 드래그 앤 드롭으로 자동 추가

viewer.html 파일과 같은 폴더 내에 이미지 파일들을 준비하고, 
이미지 파일들을 드래그 하여 JSON 텍스트 입력창에 드롭해 보세요.
JSON 텍스트가 자동 생성되고, "JSON 변경사항 적용" 을 클릭하시면 바로 준비가 됩니다.

## 폰트

나눔고딕코딩 폰트 혹은 D2Coding 폰트로 설정되어 있습니다.
설치되어 있지 않다면 구글 폰트 CDN에서 불러오게 됩니다.

# License

   Copyright 2023 HJOW

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

# 사용된 써드 파티 라이브러리 및 리소스

* jQuery - https://jquery.com/
* Google Fonts - Nanum Gothic Coding - https://fonts.google.com/specimen/Nanum+Gothic+Coding?query=Nanum+Go