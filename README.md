# GIT과 GITHUB
## GIT

- GIT : **분산** 버전 관리 시스템
- GITHUB : **원격 GIT 저장소**

### Local Git

- 저장소 생성
```bash
git init
```
- git 설정
```bash
git config user.name "YeonKyung Kim"
git config user.email kimyk7131@gmail.com
# 공용 git 설정을 하려면 -g
# 예) git config-g user.name 이름
```

- git 상태 확인
```bash
git status
```

- staging
```bash
git add .
```

- 저장소에 반영(commit)
```bash
git commit -m "First Commit"
```

- 상태 확인과 로그 확인
```bash
git status # 상태 확인
git log # 로그 확인
```

### Local Git to GitHub
- GitHub에서 저장소 생성
- 저장소 주소
    - https://github.com/kimyk0101/GITTEST.git

- 원격지 등록
```bash
git remote add origin https://github.com/kimyk0101/GITTEST.git
# git remote add 저장소이름 저장소주소
```
- PUSH
```bash
git push -u origin master # 첫번째 푸시
git push # 기본원격지 현재브랜치를 푸시
```

### From GitHub to Local Git
- 복제할 원격 저장소 주소 확보
- 복제
```bash
git clone https://github.com/kimyk0101/GITTEST.git
# git clone 원격지주소
```

- 저장소 설정

- 원격지 변경사항 FECTH (확인)

- 원격지 변경사항 PULL (내려받기)