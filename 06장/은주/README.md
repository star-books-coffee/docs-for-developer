# Chapter 6. 시각적 콘텐츠 추가하기
## 말로는 부족할 때
- 효과적인 시각적 콘텐츠는 문서화에서 위험은 높지만 보상이 큰 요소에 속한다

## 시각적 콘텐츠를 만들기 어려운 이유
- 시각적 콘텐츠가 잘 작동하면 정보가 매우 빨리 전달되어, 독자가 필요한 작업을 순식간에 훑어볼 수 있다
- 시각적 콘텐츠는 텍스트 문서를 보완하는 요소이지, 완전히 대체하는 것은 아니다
- 독자의 이해를 높이는 데 목적이 있는 것이지 그외 군더더기는 방해요소가 될 수 있다
- 가장 유용한 시각적 콘텐츠는 "독자에게" 가장 유용한 종류이다

### 이해 용이성
- 복잡한 다이어그램은 정보를 받아들이는 데 방해가 된다

### 접근성
- 비효율적인 시각적 콘텐츠는 접근성 면에서 도움이 필요한 독자를 오히려 더 어렵게 한다
  - ex) 색각 이상 - 이미지 색 대비높지 않으면 이미지 내 요소 구별이 어려움
  - 난독증 - 텍스트로 가득 찬 다이어그램은 도움이 되지 않음

### 성능
- 이미지를 로드하는데 문제가 생길 정도로 커서는 안된다

## 스크린샷 사용하기
- 주로 사용자 인터페이스를 보여주는데 도움이 된다
- 스크린샷이 유용하기 위해 체크해야 할 항목들
  - 깔끔하고 불필요한 요소가 없는지
  - 독자가 올바른 화면을 보고 있음을 알 수 있을 정도로 충분한 맥락과 함께 UI 에서 관련된 모든 부분을 포함한다
  - 너무 크지 않아야 한다
  - 너무 작지도 않아야 한다
- 이미지에 대체 텍스트를 작성함으로써 스크린 리더를 사용하는 독자의 콘텐츠 접근성을 높여준다
- 더 나은 방법은 이미지가 보여주는 내용에 대한 전체 설명을 텍스트 본문에 포함시킨다

## 일반적인 다이어그램 유형
### 상자와 화살표
- 텍스트만으로는 설명하기 어려운 개체 간의 관계나 데이터 흐름을 명확하게 보여줄 수 있다
- 어떤 선이나 화살표도 교차하지 않도록 해야 한다
- 연결선이 단방향, 또는 양방향 데이터 흐름을 나타내는지, 의존성과 같은 다른 관계를 나타내는지 명확히 해야 한다

### 순서도
- 시작~완료 지점까지 사용자를 안내하며 프로세스를 문서화하는 데 특히 유용하다
- 특정 행동 유형을 나타내는 데 동일한 모양을 사용하여 일관성을 유지하는 것이 중요하다

### 스윔레인
- 프로세스 참여자나 특정 역할을 담당하는 개체 (앱, API 등) 가 여러 개 있는 상황에서 특히 유용하다
- 누가 각 단계를 담당하는지 한눈에 쉽게 확인할 수 있다

## 다이어그램 그리기
- 다이어그램 당 하나의 아이디어만 설명해야 한다

### 먼저 종이에 그려보기
- 일부 기본적인 사용자 테스트에 유용할 수 있다

### 독자를 위한 출발점 찾기
- 독자가 다이어그램을 볼 때 어느 지점부터 보기를 원하는지도 고려해야 한다

### 레이블 사용하기

### 색상 일관성 있게 사용하기
- 의미를 전달하기 위해 색상만 사용하는 대신에 레이블까지 적절히 사용해야 한다

### 다이어그램 배치하기
- 다이어그램만 단독사용하지 말고, 해당 이미지가 나타나는 맥락에 맞는 대체 텍스트를 작성한다

### 다이어그램 게시하기
- SVG 는 확장성이 뛰어나므로 독자가 모든 화면 크기에서 다이어그램 정보에 접근하고 필요 시 확대하여 볼 수 있도록 한다

### 주변의 도움 받기
- C4 모델은 소프트웨어 아키텍처 다이어그램 작성에 유용하다
- 웹 콘텐츠 접근성 지침을 참고하여, 모든 사람이 사용할 수 있게 만들기 위한 조언을 활용한다

## 비디오 콘텐츠 만들기
- 비디오 콘텐츠는 새로운 개념을 소개할 때 유용하다
- 비디오 제작은 전문가에 맡기는 것이 더 좋다

## 시각적 콘텐츠 검토하기
- 문서를 편집하는 것과 동일하게 편집 프로세스르 거쳐야 한다
- 절대로 시각적 콘텐츠만 따로 검토하지 말고 주변 텍스트와 함께 확인해야 한다
- 시각적 콘텐츠가 이해 용이성, 접근성, 성능 요구사항을 충족함을 확인하면 동료 검토를 요청한다

## 시각적 콘텐츠 유지 관리하기
- 시각적 콘텐츠는 훨씬 빨리 구식이 될 수 있으므로 이미지를 쉽게 업데이트하고 편집할 수 있게 원본 파일을 다른 사람과 공유해야 한다

## 요약
- 이미지와 텍스트가 서로를 잘 보완하는지 확인해야 한다
- 콘텐츠 3가지 원칙을 마음에 새기자
  - 이해 용이성 : 이 콘텐츠가 독자에게 도움이 되는가?
  - 접근성 : 일부 독자에게 사용하기 어렵진 않은가?
  - 성능 : 콘텐츠 크기와 포맷이 독자에게 득이 되는가 실이 되는가?