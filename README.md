# 리눅스 정리
5

ls -a (숨김파일)
ls -l (자세히)
ls -F(파일, 디렉토리 나눠서)
ls -i
ls -m

rm(파일 삭제)
rmdir(디렉터리 삭제) / 빈 디렉터리만 허용, 내용이 있으면 바로 못지움
=> rm -r 디렉터리 명 (하위내용까지 다지움) 그래서
=> rm -ri 디렉터리 명 ( i는 질문하는 명령 ) 해서 지워야 함

man ls => ls 도움말 나옴

ex) drwxr-xr-x 5 ubuntu ubuntu 4096 Apr 1 05:03 . 

의 경우 

vi file1 파일에 입력

나갈때 esc :q! 입력하고 나감
다 모를땐 shift + z 두번

nano 얘도 적는거

cat 은 출력문

cat file1 하면 file1꺼 나옴

cat file1 > file2 1내용 2로 복붙
cat file1 >> file2 하면 밑줄에 더 붙힘


cd . 현재위치
cd .. 상위 디렉토리로 이동
cd ../.. 2단계 위 이동
그냥 cd하면 바로 홈dir로
pwd 현재 위치 확인

mv : mv test1 test2  => test1 사라지고 test2에 내용들어간채 생성
