# TIL

## 브랜치 정의
- A branch in Git is simply a lightweight movable pointer to one of these commits.

## 브랜치 합치기
- 이슈에 해당하는 작업을 수행할 때, 별도의 브랜치를 만들고 작업한다.
- 작업이 끝난 후에는, pull request를 사용해 내가 작업한 브랜치를 중요 브랜치(`main`, `master`,`development`, `devel`)로 병합시켜야 한다.

### 명령어
- `git merge`
- 주의할점: a브랜치를 b브랜치로 합치려고 할 때는 b브랜치를 체크아웃한 상태에서 `git merge a`를 입력한다.