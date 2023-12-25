
### MVVM ViewModel

- View에 필요한 데이터를 관리하여 바인딩, 비즈니스 로직을 담당해 처리

### AAC ViewModel 

- Android 생명주기를 고려하여 UI 관련 데이터를 저장하고 관리
- 화면 회전 같은 환경에서 데이터를 보관하고 관리 

### 호환성

- ObservableField나 LiveData, StateFlow를 활용해서 데이터 바인딩이 가능하다
- AAC 패턴으로 MVVM 패턴을 구현할 수 있음

