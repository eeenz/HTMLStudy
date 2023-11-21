Git & GitHub 순서
* 초기 디렉터리 생성 시 순서
1. git init <저장소 등록>
2. git branch -M main <master를 main으로 변경>
3. git remote add origin HTTP주소붙여넣기 <origin == gitHub HTTPS 주소 별칭이란 뜻>
-----------------------------------------------------------------------------------------------
* 초기 디렉터리 생성 후 작업 진행 시 순서
1. git add . <.이란? == 현재 디렉터리 안 모든 파일과 폴더를 뜻함>
2. git commit -m 'message' <현재 스테이징 된 파일의 기록명을 작성 (영어, 한글 모두 가능. 짧게 키워드 위주로 작성하기)(ex_쇼핑몰 상품 페이지를 만들었다면? git commit - m 'shop man-product end')>
3. git push origin main <origin == gitHub 주소><main == local 내컴퓨터 위치><해석 == gitHub에 local 작업물을 push 하겠다>
-----------------------------------------------------------------------------------------------
* 위 add > commit > push 순서 중간 중간 작업 확인 리눅스 명령어
1. git status <local과 staging 상태에서 작업물의 등록 상태 체크>
2. git log <commit 과 push 상태에서 작업물의 commit 기록과 업로드 정보 체크>