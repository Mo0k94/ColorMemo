# ColorMemo
#### Android CleanArchitecture, MVVM, Jetpack Compose 학습을 위한 Memo Application
---

## Skill Stack
### Architecture
  - **MVVM (Model-View-ViewModel)**
    - **설명** : MVVM은 애플리케이션의 UI를 로직과 분리하여 코드의 재사용성을 높이고, 테스트 용이성을 개선하는 아키텍쳐 패턴이다.
    - **장점**
      - 유연하고 확장 가능한 구조
      - 모듈화된 코드
      - 독립적인 테스트 기능
### Dependency Injection
  - **Hilt**
    - **설명** : Hilt는 Dagger를 기반으로 한 Android용 종속성 주입(DI) 라이브러리로, DI 설정을 단순화하고 효율적으로 관리할 수 있게 해준다.
    - **장점**
      - DI 설정의 간소화
      - 애플리케이션의 초기화 속도 향상
      - Android 특화 기능 제공
     
### Database
  - **Room**
    - **설명** : Room은 SQlite 데이터베이스 위에 추상화 계층을 제공하여 데이트베이스 작업을 쉽게 해주는 Android Jetpack Library이다.
    - **장점**
      - 컴파일 타임에서 SQL 쿼리 검증
      - 코드의 간결성 및 가독성 향상
      - LiveData와의 통합을 통한 실시간 데이터 관찰
### 동시성 프로그래밍
  - **Coroutine**
    - **설명** : Coroutine은 Kotlin에서 제공하는 경량 스레드로, 비동기 프로그래밍을 보다 쉽게 할 수 있도록 도와줍니다.
    - **장점**
      - 간단한 비동기 코드 작성
      - 메모리 누수 방지
      - 비동기 작업의 구조화
