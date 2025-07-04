## 🔧 GitHub 관리 정책

### 📌 Issue

- 기능 제안, 버그 제보, 질문 등을 등록할 수 있는 태스크 카드입니다.
- 각 이슈는 **담당자(Assignee)**, **레이블(Label)**, **마일스톤(Milestone)**, **프로젝트(Project)**와 연결되어 추적됩니다.
- **칸반 티켓**처럼 사용할 수 있으며, 하나의 이슈는 명확한 작업 단위를 표현합니다.
- 예시:
  - `[Feature] 로그인 기능 구현`
  - `[Bug] 모바일 환경에서 레이아웃 깨짐`

---

### 🎯 Milestone

- 여러 개의 Issue를 **하나의 목표**나 **기간 단위**로 그룹화합니다.
- 마일스톤에 연결된 이슈들의 진행 상황을 한눈에 확인할 수 있습니다.

| Milestone 이름    | 설명                                                 |
|-------------------|------------------------------------------------------|
| `퍼블리싱 v0.1`   | 모든 주요 UI 프레임과 구성 완료 상태를 목표로 설정        |
| `퍼블리싱 v0.2`   | 반응형, 접근성 개선 및 애니메이션 추가 단계             |
| `기능 개발 v1.0`  | 퍼블리싱된 UI에 API 연동 시작 (기능 연동 시작 단계)     |


---

### 🗂 Projects

- 프로젝트 업무 흐름을 시각화하는 **칸반 보드**를 제공합니다.
- 보드는 `Todo`, `In Progress`, `Done` 등으로 나누어 이슈 상태를 추적합니다.
- 각 칸반 열에는 Issue나 Pull Request를 드래그 앤 드롭하여 업무 상태를 업데이트할 수 있습니다.

---

### 🚀 Pull Request (PR)

- 개발 브랜치에서 작업한 내용을 **메인 브랜치(main/dev 등)** 에 병합하기 위한 요청입니다.
- PR을 통해 코드 리뷰를 진행하며, 리뷰어는 특정 커밋이나 라인에 **코멘트**를 남길 수 있습니다.
- 모든 PR은 다음 조건을 만족해야 합니다:
  - 최소 1명 이상의 리뷰어 승인
  - CI/CD 빌드 및 테스트 통과
  - 관련 이슈와 연결 (`Closes #이슈번호` 형식 사용 권장)

---

### 📎 참고 규칙

- 커밋 메시지 및 브랜치 네이밍 규칙은 별도 문서를 참고해주세요.
- 이슈, PR, 마일스톤은 항상 관련 내용을 명확하게 작성합니다.
- 리뷰는 적극적으로 참여하며, 의견 충돌 시 팀원들과 협의하여 결정합니다.

