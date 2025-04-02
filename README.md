# HTML
## Hyper Text Markup Language
### HTML은 웹문서의 구조를 담당하는 언어이다.
* HTML에서 구조는 `<>` 로 묶인 태그로 작성한다.
* `<시작태그></닫기태그>`
*`<빈태그>`
시작과 닫기태그는 한쌍의 요소로 불린다.
### HTML 구조태그
* HTML5 버전 선언하는 `<!doctype html>`
* HTML 웹 브라우저 구조 처리하는 태그들
1. `<html></html>`
2. `<head></head>`
3. `<body></body>`
----
# git&gitHub
*버전관리 프로그램 git
*버전파일, 폴더들을 관리하는 저장소 gitHub
## git 용어와 뜻
* 작업 디렉터리 : 실제 로컬 저장소(윈도우 탐색기 개념)
* 스테이징 : 깃허브에 작업 업로드 전 파일을 대기시키는 대기소
*repository: 대기소(stage)에 파일 댁기 후 최종 github 업로드 저장소
## 주의사항
* 당일 작업 시작 기준 github 저장소와 로컬저장소의 파일,폴더 상태가 같아야 한다.
* 동일한 저장소를 관리하는 사람일 경우 작업 컴퓨터가 달라도 gitconfig에 등록된 이름, 이메일이 동일해야 한다.
---
# 주요 단축키 모음
* `Ctrl +/` 한줄 주석
* `Shift +Alt+ A` 선택한 영역만 주석
---- 
# 처음 git을 이용한 github 저장소 업로드 시 해야하는 순서
1. 현재 사용중 로컬 저장소를 git 저장시 등록 `git init`
2. 위 1번 정상 등록 시 경로에 (master) 표시출력
3. master - > main으로 최상위 경로 명칭을 변경하기 위해 `git branch -main` 작성
4. github 저장소 생성 후 저장소 주소 복사
5. 현재 로컬 저장소 github 저장소 연결 `git remote add origin 주소 붙여넣기`
6. `git status` 현재 상태 확인(스테이징, 작업디렉터리, 저장소)
7. 위 6번 결과 파일이 빨강색으로 출력될 경우 `git add 파일명`스테이징 올리기
8. `git status` 위 7번에서 올린 파일이 초록색으로 변경된걸 확인
9. `git commit -m` 스테이징 파일을 저장소에 올리기 위한 기록설정
10. ` git push origin main` 깃허브 저장소에 최종파일, 폴더 업로드
11. 위 10번 처음 진행시 깃허브 계정 인증 화면 나오니 인증 진행 후 저장소 F5
----
## 다른 환경에서 이어서 작업해야 하는 경우
1. 폴더 생성하기 - > vs code 폴더 연결
2. github 저장소 주소 복사
3. vs code 돌아와서 ctrl+ J 터미널 실행 후 bash 환경 변경
4. `git clone 저장주소 붙여넣기`
5. 터미널 경로 오른쪽에 `main` 또는 `master` 표시가 있는지 확인
6. 위 5번 표시가 없다면 `cd 복제한 폴더명`
7. 자유롭게 수정 후 파일 저장
8. 터미널에 `git status` 업로드 안된 빨강색 색 확인
9. `git add 파일명` 수정한 파일 스테이지에 업로드하기
10. `git staus` 위 9번 업로드됐는지 확인
11. `git commit -m 메세지` 수정 파일에 대한 기록 메세지 작성
12. `git push origin main` 깃허브 저장소에 업로드
# html, meta에 작성하는 속성의 뜻
## html
html: 웹페이지의 전체구조를 정의하는 요소
~<html lang="ko"> 문서의 언어설정
meta: 웹페이지의 정보(메타데이터터)를 제공하는 요소
## meta의 속성과 값
<meta charset="UTF-8> 대부분의 언어를 지원. 표현할 수 있음 문자 인코딩 설정
<meta name="descripition" content="">
<meta name= "key words content="" 해당키워드를 검색시 나오게하는 것이다

