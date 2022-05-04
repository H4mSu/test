# 깃 명렁어 정리

## 깃 허브 업로드 순서
1. 수정후 저장 M 생성
2. add를 사용하자
```
git add . -> 모두 업로드
git add 파일명 -> 해당 파일만 업로드
```
3. commit 사용
```
git commit -m "깃에 올라오는 버젼 설정" 
git commit - 현재 상태 저장
```
4. 로그 한번 확인
```
git log
```
5. push로 허브에 올리기
```
git push origin master
```

## 깃 다운로드 
1.깃 클론 클릭
2.깃 클론 명령어 작성
```
git clone "url"
```
## 새로 배운 명령어
1. 깃 리셋 시키는 방법
```
git reset HEAD~1  
```
2. 터미널에서 저장소 이동 시키는 방법
```
cd ../  
```
3. 깃 원격 url 주소확인 방법
```
git remote add origin url  
git remote set-url origin "url주소"  
git remote -v  
```
4. 깃 push 상황때 오류 해결 방법
```
1. 강제push
git push origin master -force
2. 관련없는 걸 허락해서 풀 시키기
git pull origin master --allow-unrelated-histories 
```