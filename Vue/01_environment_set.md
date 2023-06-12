# 개발환경 설정 및 프로젝트 생성

## 1. node.js 설치

1. 윈도우
    - https://nodejs.org/en 에서 Recommended For Most Users 버전 다운로드 (검증된 버전)
    - 설치파일 실행 후 완료되면 cmd창에서 **`node -v`** 명령어 실행, 정상적으로 버전 출력되는지 확인
2. 맥 (homebrew)
    - brew install node 로 설치 후 **`node -v`** 명령어 실행, 정상적으로 버전 출력되는지 확인

<br>

## 2. vue CLI 설치

`npm insstall -g @vue/cli`

-   cmd 또는 터미널에서 위 명령어 실행
-   설치 후 **`vue-V`** 명령어 실행, 정상적으로 버전 출력되는지 확인

<br>

## 3. 프로젝트 생성

`vue create 프로젝트명`

-   위 명령어로 프로젝트 생성
-   프로젝트명은 **케밥케이스**로 작성할 것
-   터미널에서 방향키로 버전 선택 후 엔터

<br>

## 4. 실행

`cd 프로젝트 디렉토리`
<br>
`npm run serve`

-   위 명령어로 프로젝트 디렉토리로 이동한 후 서버 실행
-   터미널에 표시된 주소로 접속했을 때 Welcome to Your Vue.js App이 보인다면 성공
-   서버 종료는 터미널에서 **`ctrl+c`**
