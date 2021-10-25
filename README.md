# do-it-git

![gitcommands](https://miro.medium.com/max/576/1*VQQoNths6TklkJlyBn5UXA.png)  
출처 :[https://medium.com/@dilankam/most-frequently-used-git-commands-3f24cd4b484a]

git 명령어

1. 환경 설정
```
$ git config --global user.name "xxxxx"
$ git config --global user.email "xxxxx@xxxxx.xxx"
```

2. git 초기화 하기  
- 깃을 사용할 수 있도록 디렉토리를 초기화
```
$ git init
```
- 디렉토리 생성과 동시에 초기화
```
$ git init 디렉토리명
```

3. 상태 / 로그 확인

```
$ git status
$ git log
```

4. commit 
```
$ git commit -m "message1"
```

5. 작업 트리에서 수정한 파일 되돌리기  
- 스테이지에 올라가지 않은 현재 디렉토리의 변경사항 취소

```
$ git checkout --파일명
```

6. 스테이지에서 내리기
```
$ git reset HEAD 파일명
```

7. 최신 커밋 되돌리기
```
$ git reset HEAD^
```

8. 브랜치 생성하기
```
$ git branch 브랜치명
```

9. 브랜치 변경하기
```
$ git checkout 브랜치명
```

10. 커밋 취소하기
```
$ git reset 커밋해시
```
11. 원격 저장소 연결하기
```
$ git remote add origin 복사한 주소
```
12. 원격 저장소에 파일 올리기
```
$ git push -u origin master
$ git push # 한번이라도 푸시 했다면
```

13. 원격저장소에서 파일내려받기
```
$ git pull origin master
```


