# TIL
## DONE


### shell command
cd Documents/ : 도큐먼츠로 들어가는 명령어

mkdir dev : dev라는 디렉토리(폴터)만들기

cd .. : 전 디렉토리로 돌아가기

pwd : 현재 디렉토리의 경로를 알고 싶을 때


touch readme.md : readme.md라는 파일 생성

mv readme.md bin/ : readme.md 파일을 bin 폴더로 이동

mv readme.md ./README.txt : readme.md파일 이름을 README.txt로 바꿔라

cp readme.md bin/ : readme.md 파일을 bin 폴더로 복사

rm README.txt : README.txt파일 제거

rm -rf bin/: 경고 사인없이 디렉토리 삭제

cat readme.md : 파일의 내용을 출력한다

vi readme.md : readme.md파일을 vim으로 열기

### vim comman

i = insert mode

v = visual mode

ESC = back to normal mode

d - delete

dd - delete a line

Y - yank(copy)

YY - yank a line

p - paste

u - undo

a - append

A - append from end of line

o - open line(under)

O - open line(upper)

H - move to the top ofo the screen

L - move to the bottom of the screen

### What if we want to write some codes

```python
print('hello, world!')
```

### What is git?

git과 github는 각각 커피와 커피숍같다고 보면 됨

git 자체는 항상 파일들의 변화를 주시하고 있음

큰 장점은 같은 파일에 대한 각기 다른 버전을 보관 가능

git은 다시 말해 각기 다른 결말을 가지고 있는 파일이 있다면

공통되는 부분의 수정을 한번에 할 수 있다는 뜻

### Why is need it?

협업이 가장 큰 장점이기 때문이다.

하나의 파일을 나와 또다른 에디터가 서로의 변경사항과 충돌할 일 x


### How to use git?

이해한대로 기록하자면

1.내 컴퓨터에서 작업을 진행

2.gid add 를 통해 staging area로 이송

3.git commit을 통해 local repo로 이송

4.작동되는 것을 알았다면 git push를 통해 remote repo
  
  즉 github으로 보내 공유

5.반대로  git pull할 수 있음

#### Start project with git init

git init라는 명령어를 통해 로컬 폴더에 git파일이 생성됨과 동시에

git을 사용할 수 있게 된다.

항상 git status 명령어를 통해 현재 파일들의 상태를 확인하자

또 한가지 알아야 할 사실은 commit을 해야지만 git에 파일이 저장된다.(git이 내가 관리해야하는 파일이구나 라고 인지하는 단계)

빨간색으로 표시되는 Untracked files:....은 commit이 안된 파일

git commit -m [explanation]은 -m옵션이 다음에 설명이 나온다는 것을 알려주는 것임


#### Start project with git clone

clone은 간단하다.

git clone [복사하고 싶은 깃허브주소]를 치면 그대로 내 컴퓨터에 복사가 된다.
