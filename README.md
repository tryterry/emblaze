# ✨ emblaze
![alt text](resource/mokup.png)


### emblaze는 조명 제어 도구로, 사용자가 손쉽게 조명을 관리할 수 있도록 지원합니다.

emblaze는 [BLE Mesh](./BLE_MESH.md) 네트워크를 기반으로 한 스마트 조명 제어 솔루션입니다.대규모 시설에서도 간단한 무선 네트워크를 활용하여 효율적인 조명 제어가 가능합니다.

⠀📌 주요 기능
* **조명 개별 및 그룹 제어**
* **조명 설정 변경 및 저장**
* **조명 제어 스케줄링**
* **도면 UI를 통한 직관적인 사용성 제공**

⠀🔐 요구 권한
* **위치 액세스**: IoT 장치를 검색하기 위해 사용
* **근처 기기 액세스**: IoT 장치와 BLE Mesh 네트워크 연결

&nbsp;

<video controls src="resource/gif_home.mp4" title="Title"></video>

# 🛠️ 개발 환경
* **IDE**: Android Studio
* **SDK Version**:
  * minSdkVersion : 25 (Android 7.1, Nougat)
  * targetSdkVersion : 34 (Android 14)

&nbsp;

# 📚 기술 스택
### 📌 언어 & 프레임워크
* **Kotlin**

⠀🔄 비동기 처리
* **RxJava**
* **Coroutine**
* **Flow**

⠀🌐 네트워크 통신
* **Retrofit**

⠀⚙️ 의존성 주입
* **Hilt**

⠀💾 데이터 저장소
* **Room** (로컬 데이터베이스)
* **Preference DataStore** (설정 데이터 저장)

⠀📊 상태 관리 & UI
* **ViewModel**
* **LiveData**

⠀🖼️ 이미지 로딩
* **Glide**