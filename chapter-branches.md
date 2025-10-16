# Git & Github 게임 답안지

## Branches

### 1. Moving through time

1.  마지막 커밋 위치에서 체크아웃 , git checkout 457db0cc

2.  piggy_bank 파일 수정, echo "This piggy bank belongs to the big sister.It contains 10 coins." > piggy_bank

3.  little_sister 파일 수정, echo "A young girl with brown, curly hair." > little_sister

4.  변경 내용 커밋, git commit -am "commit"

### 2. Make parallel commits

1.The child climbs somewhere 위치에서 체크아웃, git checkout 3fc029

2.  cage/lion 파일 수정, echo "Looks happy. :) " > cage/lion

3.  변경 내용 커밋, git commit -am "commit"

### 3. Creating branches

1.  콘서트 위치로 이동, git checkout

2.  콘서트 브랜치 생성, git branch concert

3.  생일파티 위치로 이동, git checkout

4.  생일파티 브랜치 생성, git branch birthday

### 4. Branches grows with you!

1. 생일파티 위치로 이동, git checkout 2080ea22

2. you 파일 수정 후 커밋, git add . git commit -m "birthday commit"

3. 콘서트 위치로 이동, git checkout concert

4. you 파일 수정 후 커밋, git add . git commit -m "concert commit"

### 5. Deleting branches

1. friend 브랜치 삭제, git branch -D friend

2. ice-cream 브랜치 삭제, git branch -D ice-cream

3. music 브랜치 삭제, git branch -D music

