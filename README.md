# CMD 저장 정리!
```
1. cd 경로
2. git add .
3. git commit -m ""
4. git push
```

## 📌 충돌시 
```
git pull origin main
git push origin main
```

## 📌 Github 프로젝트 생성
```
git init
git add [파일명]
git commit
```

## 📌 Github에서 데이터 가져오기
   ```
git clone [url]
git clone https://github.com/[내 이름]/[저장소명].git
  ```
  
  
## 📌 Git Hub commit

1. 파일 전체 저장

```
git add *
git commit -m "커밋 메세지 입력"
git push origin master(main)
```

2. 파일 일부 저장

```
git add [파일명]
git commit -m "커밋 메세지 입력"
git push origin master(main)
```

## 📌 git hub 새로운 파일 업로드 하는 방법


### 1. git hub에서 올릴 파일 먼저 생성

</br>

### 2. 내 컴퓨터에서 원격 저장소 가져오기

저장할 파일에서 마우스 우클릭 + git bash here

</br>

### 3. git 설치 후 초기 설정을 위해

 
```
git config --global user.name [이름]
git config --global user.email [이메일]
```
 

을 차례로 입력한 후 Enter을 누른다.

</br>

### 4. 앞서 생성한 저장소를 가져오기 위해 
```
git clone http://github.com/[이름]/[저장소 명].git
```
 

를 입력해준다.

그러면 저장소 이름과 같은 폴더가 로컬 저장소에 생기고,

그 안에는 *.git*라는 폴더가 생긴걸 확인할 수 있다.

(만약 안보이면 보기 -> 숨긴 항목 체크)

</br>

### 5. 방금 생성한 로컬 저장소에 업로드할 파일을 넣어준다.

*.git* 이 있는 경로로 저장할 파일 전체 이동

</br>

### 6. .git이 있는 파일에서 빈 공간 우클릭

 *git bash here*로 다시 창을 열어 준 뒤 ```git status``` 명령어로 현재 저장소에 있는 파일 상태를 확인

 
만약 파일이 빨갛게 표시되면서 추적되지 않는 파일이라고 하면

깃허브의 저장소(원격 저장소)와 현재 내 컴퓨터 상의 저장소(로컬 저장소)가 일치하지 않아 추가 한 파일의 존재를 알 수 없기 때문이다.


그럴 경우 문제의 파일 이름을 확인하고
```
git add [파일명]
```
입력한 후 ```git status``` 로 다시 파일 상태를 확인해보면 파일명이 초록색으로 바뀐 모습을 볼 수 있다.

</br>

### 7. git commit
```
git commit -m "커밋 메세지 입력"
```
저장할 내용 메모

</br>

### 8. git push
```
git push origin main
```

또는

```
git push origin master
```
입력해줘서 저장 완료!
