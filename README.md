# Dacon_study
DNA dacon study <br>
<br>

## 이전 변동 내용 가져오기
```
git pull
```

## 현재 브랜치(현재 위치) 및 해당 레포에 존재하는 모든 브랜치 확인
- 현재 브랜치는 혼자 다른색으로 나타내줌.
```
git branch
```

## 브랜치 이동
```
git checkout 이동하고 싶은 브랜치명
```

## 브랜치 합병
```
git checkout 합병시켜야하는 브랜치명
git merge 합병시킬 내용이 들어있는 브랜치명
git push
```

혹은 github의 해당레포에 가서 main branch로 이동 후 상단의 [compare & pull request] 버튼 클릭 <br>
[Pull requests] tab으로 이동 <br>
[open] tab 아래 있는 pull reque 선택 <br>
[merge pull request] 버튼 <br>
[confirm request] 버튼 <br>
-> 해당 브랜치 closed됨. (해당 pull request는 [closed] tab으로 이동) <br>
<br>

## 그 닫힌 브랜치 복구하는 방법
[closed] tab 가서 해당 request가서 restore branch 클릭

<br>

## 커밋메세지 변경
- [바로 이전 커밋메세지 수정](https://backlog.com/git-tutorial/kr/reference/log.html) <br>
```
git commit --amend
s
커밋메세지 수정
esc + :wq + enter
```
[참고1](https://velog.io/@mayinjanuary/git-%EC%BB%A4%EB%B0%8B-%EB%A9%94%EC%84%B8%EC%A7%80-%EC%88%98%EC%A0%95%ED%95%98%EA%B8%B0-changing-commit-message) <br>

[참고2; git commit --amend -m '마지막 커밋 수정'](https://jw910911.tistory.com/77) <br>

[참고3; 리모트](https://xtring-dev.tistory.com/entry/Git-%EC%9D%B4%EB%AF%B8-commit%ED%95%9C-%EB%A9%94%EC%84%B8%EC%A7%80-%EC%88%98%EC%A0%95%ED%95%98%EA%B8%B0-%EB%B0%94%EB%A1%9C-%EC%9D%B4%EC%A0%84%EA%B7%B8-%EC%A0%84%EB%A6%AC%EB%AA%A8%ED%8A%B8-commit) <br>

[참고4; 삽질기록](https://holika.tistory.com/entry/Git-%EC%82%BD%EC%A7%88%EA%B8%B0%EB%A1%9D-Git-push-%EC%9D%B4%ED%9B%84%EC%97%90-%EC%BB%A4%EB%B0%8B-%EB%A9%94%EC%8B%9C%EC%A7%80%EB%A5%BC-%EC%88%98%EC%A0%95%ED%95%98%EA%B3%A0-%EC%8B%B6%EC%9D%84-%EB%95%8C) <br>