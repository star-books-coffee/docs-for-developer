# Chapter 4. 문서 편집하기
## 사용자의 니즈에 맞춰 편집하기
- 초안 작성은 모든 아이디어를 써내려가는 과정이라면, 편집은 문서를 살펴보고 사용자의 니즈를 충족하도록 수정하는 과정이다
- 작성과 편집을 동시에 하면 진행속도가 느리기 때문에, 창작과 평가 과정을 분리하면 작성한 내용을 비판적인 시각으로 검토할 수 있다
- 편집은 다른 사람과 콘텐츠를 공유하고 피드백을 수집하는 협업 프로세스이다

## 편집에 대한 여러 가지 접근법
- **개선하려는 한가지 측면에 집중하여, 한번에 하나씩 점검하는 것이 좋다**
- 기술적 정확성, 완전성, 구조, 명확성과 간결성 측면으로 순서대로 편집하면, 기술적 정확성부터 사용자의 니즈를 향해 점진적으로 나아갈 수 있다
- 편집할 때는 이 정보를 처음 접하는 사람처럼 문서를 읽어야 한다

### 기술적 정확성을 위한 편집
- 다음 질문에 대답할 수 있어야 한다
  - 지시사항을 따라가면 약속한 결과를 얻을 수 있는가
  - 혼동을 주는 기술적 은어나 용어가 있는가
  - 코드의 함수, 파라미터, 엔드포인트가 올바르게 명명되고 설명되는가
- 여러 운영 체제 및 개발 환경 지원시 문서에 명시한다
- 마찰 로그를 만들었을 경우 임시 대처법이나 문제를 문서에 반영했는지 확인한다
- 사용자에게 미리 경고해야 할 사항 (장애, 데이터 손실, 신체적 상해) 이 있는지 확인해야 한다

### 완전성을 위한 편집
- 사용자가 성공하는 데 필요한 모든 정보가 포함되어 있는지 확인해야 한다
- 사용자와 사용자의 소프트웨어 사용방식을 고려해야 한다
  - ex) 운영체제, 소프트웨어 버전
- 제약 사항을 명확히 기록해야 한다
  - ex) 버전별 제약사항, 만료 정보
- 완전성은 모든것을 이야기한다는 의미가 아니라 사람들에게 도움을 주기에 충분한 정보를 포함하되 원하는 것을 찾을 수 없을 정도로 지나치게 많은 것을 포함하지는 않아야 한다는 의미이다.

### 구조 측면에서의 편집
- 이 문서가 무엇에 관한 것이고, 주제가 어떻게 분류되어 있는지가 독자에게 명확한지 확인 해야 한다.
- 답변해보면 좋을 질문들
  - 문서, 섹션 제목에서 문서가 무엇에 관한 것인지 명확히 드러나는가
  - 문서가 일관되고 논리적인 방식으로 구성되었는가
  - 문서에 다른 문서에 포함시키는 것이 더 적절한 섹션이 있는가
  - 템플릿이 있다면, 템플릿을 충실히 따르는가
- 구조 측면 편집 단계에서는 자신이 세운 문서화 계획을 잘 따르고 있는지 확인하기 좋은 시점이다
- 독자가 콘텐츠 읽기 전, 후에 수행해야 할 작업을 나타내고 있는지도 확인해야 한다
- 필수 조건 단계가 있다면 명확히 제시해야 한다.
  - ex) 관리자 권한 필요, API 설정 완료 필요
- 독자가 문서를 읽은 후 일반적으로 수행해야 하는 다음 단계나 필요한 추가정보가 있다면 해당 링크를 나열해야 한다

### 명확성과 간결성을 위한 편집
- 한 줄씩 검토하여 각 문장과 단락이 이해하기 쉬운지 확인해야 한다
- 언어편집의 모든 고전적 요소인 문법, 어조, 간결함을 고려해야 한다

## 편집 프로세스 만들기
- 편집프로세스는 검토를 위한 일련의 공통 절차와 표준을 마련하게 해준다.
    - 문서 직접 검토 -> 동료 검토 요청 -> 기술적 검토 요청 (필요시)
- 새로운 관점을 가진 사람이 객관적인 피드백을 제공할 수 있다.

### 작성한 문서 먼저 검토하기
- 편집 체크리스트를 사용하여 자신이 만든 콘텐츠를 수월하게 검토한다
- 체크리스트 항목 예시
  - 문서 제목이 짧고 구체적
  - 섹션 제목이 논리적 순서로 배치되며 일관성이 있다
  - 문서 목적이 첫번째 단락에 설명
  - 절차가 테스트되었고 잘 작동
  - 기술적 개념에 대한 설명/링크 제공
  - 템플릿 구조를 따르는 문서
  - 작동하는 링크
  - 맞춤법 및 문법 검사기 실행 완료
  - 명확하고 유용한 그래픽, 이미지
  - 모든 필수조건과 다음단계가 명시됨

### 동료 검토 요청하기
- 어떤 종류의 피드백을 원하는지 검토자에게 알린다
- 특정 피드백을 요청하는 것 외에, 어떤 방법으로 피드백 받고 싶은지 구체적으로 알려주는 것도 중요하다
- 코드리뷰와 유사하게 반복적 검토 프로세스로 문서에 대해 검토를 요청할 수 있다

### 기술적 검토 요청하기
- 특정 주제의 기술 전문가가 문서르 검토하고 세부 정보를 추가하거나 확인하는 과정을 거친다
- 2가지 이상의 기술을 통합하는 제품을 문서화할 때 특히 중요하다

## 피드백 받아서 반영하기
- 가장 많은 피드백을 준 사람부터 시작하여 다른 검토자가 제공한 피드백까지 미리 처리한다
- 피드백 수락 여부와 무관하게 검토자의 도움에 감사를 표해야 한다

## 좋은 피드백 제공하기
- 동료 검토는 건설적인 태도로 접근할 때 가장 효과적이다
- 다른 사람의 실수를 고치는 게 아니라 그들의 이해에 보탬을 주는 과정으로 바라봐야 한다
- 비판을 제기한 다음에는 개선을 위한 구체적인 제안을 제공해야 한다
- 건설적인 제안은 문제의 해결책이 될 거라고 생각하는 방안에 대한 맥락을 추가로 제공할 수 있다
- 좋은 피드백을 제공하기 위해 명심해야 할 것
  - 사람이 아니라 아이디어에 집중하기
  - 건설적인 제안을 덧붙이기
  - 피드백을 받는 사람이 피드백에 반응할 시간 주기
- 좋다고 생각하는 점을 언급해도 된다