

## MVVM 패턴

- view, viewModel, Model을 분리
- 뷰와 모델간의 의존성 감소
- 모델은 데이터와 비즈니스 로직을 처리
- 뷰는 사용자 인터페이스 표시
- 뷰모델은 뷰와 모델 사이의 매겣 역할을 수행
- 뷰모델은 뷰와 완전히 분리되어 있으며, 데이터 바인딩을 통해 뷰와 동기화 처리
- 뷰에 대한 상태와 동작을 관리하고 사용자 입력 및 이벤트 처리

### 장점

- 데이터 바인딩을 통해 뷰와 모델 사이의 동기화를 자동으로 처리
- 유연하고 확장 가능한 구조를 제공하며 UI와 비즈니스 로직을 분리 

### 단점

- 초기 학습 곡선이 높으며, 뷰 모델에 많은 코드가 포함되어 관리가 어려울 수 있음
- 애플리케이션의 규모가 작거나 단순한 경우 과도한 추상화 발생 


