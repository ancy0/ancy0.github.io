# Create a Blog (feat. Github Pages)

## 1. Github Page 시작하기
1. Repository 생성
- Github에 ancy0.github.io 이름의 Repository 생성

2. Local-Remote Repository 연동

3. 예시 문서(index.html) 작성하여 git add/commit/push 하기

4. Github Page 설정 확인
- Repository Settings > Pages
- 중간의 주소에 접속

5. 이전에 작성했던 예시 문서가 나타나면 성공
<img width="465" alt="0" src="https://user-images.githubusercontent.com/84322890/146318007-e2987657-f96a-44c8-a5a6-36021d7b96a0.png">

## 2. Jekyll 반영하기
1. Jekyll 설치 확인
<img width="576" alt="1 j 설치확인" src="https://user-images.githubusercontent.com/84322890/146315774-c7045fa6-0202-405f-91f5-63d02e0a7d20.png">
2.  현재 디렉토리(.)에 Jekyll 설치
<img width="576" alt="2 현재 디렉토리에 j 설치" src="https://user-images.githubusercontent.com/84322890/146315823-f6e0e4cd-b8e7-4d1d-9d9a-2b5437db4061.png">

3. (bundle exec) jekyll serve 실행 후, localhost:4000접속
- 에러발생
 <img width="438" alt="3 에러발생" src="https://user-images.githubusercontent.com/84322890/146315874-09dbe9c0-1c40-467d-8d48-c22f604452d8.png">
- bundle add webrick 으로 해결
<img width="438" alt="4 에러해결" src="https://user-images.githubusercontent.com/84322890/146316133-132bbec7-a33e-479d-b652-6aa7709f0721.png">
- 다시 (bundle exec) jekyll serve 실행
<img width="475" alt="5 4000" src="https://user-images.githubusercontent.com/84322890/146316386-e9cc8b10-5e96-4bf5-a58b-31499c83740f.png">
- localhost:4000접속
<img width="456" alt="6 j 사이트생성 성공" src="https://user-images.githubusercontent.com/84322890/146316471-15415331-19d6-4bfb-ba0f-9e49a976e636.png">

## 3. 테마 적용하기
1. 테마 선택하기
<img width="678" alt="7 테마선택" src="https://user-images.githubusercontent.com/84322890/146316550-33f8d23c-298d-4ab4-aba5-11e4cad57f62.png">

2. 테마 적용하기
<img width="612" alt="8 테마적용" src="https://user-images.githubusercontent.com/84322890/146316686-a797a2f4-dfd7-46f3-90fb-7e0207356e0e.png">

## 4. 블로그 정보 수정 및 내용 추가
1.  _config.yml 에서 정보 수정
- 기존에 입력되어 있던 내용 대신 자신에게 맞는 정보를 입력
- 수정 내용으로는 블로그의 title, email 주소 등이 있음
<img width="847" alt="9 config" src="https://user-images.githubusercontent.com/84322890/146323933-35d35c0c-b51d-4ddc-acae-819bf8155e6e.png">

2. 블로그 project 추가
- 템플릿의 프로젝트 삭제 후 새로 입력
<img width="712" alt="10 pj" src="https://user-images.githubusercontent.com/84322890/146324136-189a57e7-8621-42d8-97c9-6fc5552cd9f5.png">