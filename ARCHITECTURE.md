# 앱 아키텍쳐 및 구조 설명

앱 아키텍처 설계에서는 MVVM 패턴과 Clean Architecture를 적용하여 코드의 가독성, 유지보수성, 확장성을 높였습니다. MVVM 패턴을 통해 UI와 비즈니스 로직을 분리하여 더 직관적이고 유연한 구조를 만들었으며, Clean Architecture는 앱을 여러 계층으로 나누어 각 계층의 책임을 명확히 하여 확장 가능한 구조를 구현했습니다.

또한, Hilt를 의존성 주입 라이브러리로 사용하여 객체 생성과 관리의 책임을 분리하고, 코드 간의 의존성을 줄였습니다.

### 앱 구조
![alt text](resource/archi.png)
&nbsp;
---

### MeshNetworkRespository
BleMeshManager와 MeshManagerApi의 콜백 인터페이스를 오버라이딩하여 Bluetooth 메세지를 메시 프로토콜 메세지로 변환 처리

![alt text](resource/archi_mesh.png)
&nbsp;
---

### EmblazeApiRepository
네트워크 통신에 필요한 각 서비스별 요청 메소드 관리

![alt text](resource/archi_api.png)
&nbsp;
---

### ScheduleRepository
조명 제어 스케줄 데이터 관리

![alt text](resource/archi_schedule.png)
&nbsp;
---

### AppDataRepsoitory
앱 기본 설정 및 글로벌 데이터 관리

![alt text](resource/archi_data.png)
&nbsp;