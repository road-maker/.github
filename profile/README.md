# 나만의 무기: RoadMaker | KraftonJungle
## 기본 Rule
- 10:00 ~ 10:20 데일리 미팅(오전)
- 22:00 ~ 22:20 데일리 미팅(오후)
- 매주 (금) 위클리 미팅 및 주간 회고
## Commit Convention
- 작업 내용을 쉽게 파악하고, 유지보수할 수 있도록 정하는 Commit Message 규칙이다.
  - 커뮤니케이션 효율성 증대
  - 문제 해결 속도 향상
  - 문서화 기능
- 본 프로젝트에서는 간소하게나마 **AngularJS commit Convention**을 따르고자 한다.
### Commit message & Description
> **[#Issue Number] Type: Commit Title**
>     Description goes on here
### Commit Rules
> Reference: [커밋을 잘게 쪼개자 - 커밋은 언제 하는 것이 가장 좋을까?](https://jaeheon.kr/257)
1. 커밋 단위는 메세지 한 줄로 설명할 수 있는 행동
2. 간단한 커밋을 지향해야 한다: 한 커밋에 한 액션
### Commit Type and Description

<!--StartFragment-->

Type | Description
-- | --
Feat | 새로운 기능 추가
Fix | 버그 수정 또는 typo
Refactor | 리팩토링
Design | CSS 등 사용자 UI 디자인 변경
Comment | 필요한 주석 추가 및 변경
Style | 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우(함수/변수명 변경은 포함)
Test | 테스트(테스트 코드 추가/수정/삭제), 테스트 리팩토링
Chore | 소스 코드를 건드리지 않는 변경(빌드 스크립트 수정, assets image, 패키지 매니저 등)
Init | 프로젝트 초기 생성
Rename | 파일 혹은 폴더명을 수정하거나 옮기는 경우
Remove | 파일을 삭제하는 작업만 수행하는 경우
Docs | 문서 작업, 수정
Build | 빌드 관련 파일 수정
CI | CI 관련 설정 수정

<!--EndFragment-->

## Issue 발생부터 완료까지
Github에서는 Github Issue기능을 PR과 연동하여 협업 도구로 사용할 수 있다.
1. Issue 생성: assignee, lable, 중요도, back/front/devops, 레포지토리 설정
2. Branch 생성 시 해당 IssueNumber를 넣어 작성하면 연동된다.
3. Pull Request를 작성할 때 **[Keyword] + #[IssueNumber]** 를 작성하면 연동된다.- Keyword: close, closes, closed- fix, fixes, fiexed- resolve, resoves, resolved
- PR이 머지될 경우 자동으로 해당 이슈가 close된다.
- 키워드 없이 issue 번호만 작성하면 머지 되어도 issue는 종료되지 않는다.
