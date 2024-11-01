# EXP 미션

## Git 브랜치 전략

### Git Flow

- 개요
  - main: 안정된 배포 버전
  - dev: 배포 전 테스트와 각 기능이 병합되는 브랜치
  - feature: 각 기능을 개발하는 브랜치, dev에서 분기해 dev로 PR을 통해 머지됨
  - hotfix: main에 심각한 오류가 발생되어 빠른 수정이 필요할 때만 사용
- Git Flow를 선택한 이유
  - main과 dev가 깔끔하게 관리됨.
  - 각 단계별로 PR을 통해 코드리뷰가 가능.

### 브랜치 운영 규칙

1. 상위 브랜치로 머지 시 무조건 PR
2. 각 PR은 squah and merge를 통해 dev의 로그를 깔끔하게 관리
3. force push는 금지
4. 머지 할때는 2인 이상의 Approve 필수
