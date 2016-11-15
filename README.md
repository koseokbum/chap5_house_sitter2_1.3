# 사용하는 방법

## 실행 

이것은 원본의 `house-sitter2` 앱을 Meteor Version 1.4.2.1로 수정해 본 것이다. 


이 깃저장소를 클론닝 한 이후에 다음과 같이 시행한다.


    $ git clone https://github.com/koseokbum/chap5_house_sitter2_1.3.git

그리고 해당 앱 디렉터리로 이동한 다음, 다음을 실행한다.


    $ meteor npm install
    $ meteor run

## 바꾼 부분

책의 앞 부분에 있는 저자 부록 부분에서 설명한 미티어 공식 사이트의 `simple-todos` 앱과 같이 `imports` 등의 디렉터리를 만들어 다시 정리했다. 주로 바뀐 부분은 다음과 같다. 


- 컬렉션을 `imports/api/houses.js` 파일에 만들고 이것을 클라언트와 서버에서 임포트한다. 

- 클라이언트 부분을 `imports/ui/app.js`, `imports/ui/app.html`으로 옮겨놓았다. 

- `Tracker`, `Session`이 필요한 부분(`imports/ui/app.js`)에서 이것들을 임포트하였다. 

