## 📚오늘의 git 명령어 정리

> **1.** **`git init`**
> :특정 디렉토리에 가서 git init 명령어를 작성하면 해당 디렉토리에 git이 생성된다.(ls -a 명령어를 작성하면 .git 디렉토리가 생성된 것을 확인할 수 있다.)

> **2.** **`git add`**
> :git add 명령어는 commit 단계 이전의 공간인 staging area에 올려 git에 의해 추적될 수 있게하는 명령어다.

> **3.** **`git restore`**
> :git restore 명령어는 git의 파일 조작(특정 커밋으로 되돌리기, Unstaging 시키기)만을 위한 기능을 지원하는 명령어다. git restore --staged <파일 명>을 입력하면 staging area에 올라간 파일을 다시 unstageing 된다.(add된게 취소)

> **4.** **`git remote`**
> :git remote 명령어는 -v 옵션과 함께 사용하면 원격저장소 목록을 볼 수 있다. git remote origin <원격 저장소 주소>를 입력하면 origin이라는 이름으로 원격 저장소가 등록되었다는 의미이다.

> **5.** **`git branch`**
> :git branch 명령어는 옵션없이 git branch만 입력하면 현재 내가 있는 브랜치를 알 수 있다. 만약 git branch <새로운 브랜치>를 입력하면 branch 뒤에 입력된 이름으로 브랜치가 생성된다.

> **6.** **`git checkout`**
> :git checkout 명령어는 현재 브랜치에서 다른 브랜치로 이동할 때 사용하는 명령어다.

> **7.** **`git commit -m`**
> :git이 디렉토리의 변경 내용을 저장하는 단위를 commit이라고 부르는데, 이처럼 staging area에 두어야만 비로소 commit을 만들 수 있다.-m 옵션과 함께 사용하면 터미널에서 바로 commit 메시지를 입력할 수 있다.

> **8.** **`git push`**
> :git push 명령어는 로컬에서 작업을 하고 commit을 만든 뒤 원격으로 내용을 업로드 하는 명령어다.

> **9.** **`git status`**
> :git status 명령어를 입력하면 현재 디렉토리에서 staging area에 올라가 추적이되는 파일과 올라가지 못해 추적되지 않는 파일의 목록들을 보여준다.
