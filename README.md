# newspaper-layout

1.위지위그:깃허브홈피

2.터미널모드(수동)
-로컬저장소(현재 내 pc)
-원격저장소(깃허브 repository)
입력순서
  git init 로컬저장소 초기화
  echo "# newspaper-layout" >> README.md 생성
  git branch -M main 저장소>브랜치 기본경로 생성
  git remote add origin https://github.com/leesbee/newspaper-layout.git >> remote(원격)저장소 연결
  git config --global user.email 깃허브 계정이메일주소 ->인증(처음에만하면됨)
  git add . 업데이트 할 파일 등록 
  git status 업데이트 대기 등록된 파일확인(초록색으로보임)
  git commit -m "첫 업로드"  ->변경사항을 최종반영, 깃허브 업로드 최종 준비단계 
  
  git push -u origin main 깃허브에 업로드

##다음 업데이트부터는 
-git add . 
-git commit -m "업데이트 설명글"
-git push -u origin main