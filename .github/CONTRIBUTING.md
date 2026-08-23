# Commit Ground Rules

1. `main`, `develop` 브랜치에서 직접 수정하지 않습니다.
2. 앱이 실행되지 않는 브랜치는 push하지 않습니다.
3. 다른 팀원의 승인 전에는 merge하지 않습니다.
4. 다른 팀원의 코드를 바꾸기 전에 공유합니다.
5. merge가 끝난 브랜치는 삭제합니다.

프로젝트 기술에 맞는 검사 도구를 선택해주세요.

- FE 또는 Express: Husky와 commitlint
- Spring Boot: Git hooks와 Gradle 또는 Maven 검사
