TIL
폴더 생성  : mkdir [폴더명]
파일생성 : touch [파일명]
폴더 접근 : cd [폴더명] 
모든 파일 보기 : ls -a 
파일 열기 : open . 
package.json 파일생성 : npm init -y 
상태 확인  : git status
두번째 나무로 가서 파일추적 : git add [파일명] 
첫번째 나무로 다시 돌아가는 법 : git rm —cached [파일명] 
모든 파일 추적 : git add *
커밋하는법(최종확정본) : git commit -m "커밋한 내용 텍스트명" 
커밋한 내용 로그 확인 : git log 
한줄로 로그 확인 : git log —oneline 
커밋에서 다시 2번째로 돌아가는법? : git reset HEAD [파일명] 
파일 전상태로 되돌리는법 : git checkout -- [파일명] 
[2단계나무로 들어간 아이들은 체크아웃을 통해 돌려도 변경되지 않는다] 
2단계 나무로 들어간 아이들 모두 돌리기 : git reset —hard 
브랜치 파는법 : git branch [브랜치명] 
브랜치 파고, 새로운브랜치로 이동 : git checkout -b [브랜치명]
브랜치로 왔다갔다 하는법 : git checkout [브랜치명] 
브랜치 비교하는법 : git diff [기존브랜치명] [비교대상 브랜치명]
브랜치 삭제하는법 : git branch -d [브랜치명]
병합 하는법 : git merge [브래치명]
workflow 
첫번째 나무 : working directory (작업영역) 
두번째 나무 : index ( 준비영역 : Staging Area)  → add 명령어를 사용하면 여기로 온다 
>>이파일을 깃이 관리하겠다 라는 의미 
마지막 나무 : head ( 최종확정본 : Commit)→ commit 하면 헤드영역에 뿌려준다.
>> 이 파일이 깃에 저장
