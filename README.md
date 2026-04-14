# About Me

안드로이드 앱의 **안정성**과 **사용자 경험**을 개선해 온 개발자 **유진**입니다.

기능 구현에 그치지 않고,  
서비스가 **안정적으로 동작하는 구조**, **운영 과정의 비효율**, **재발하지 않는 해결 방식**까지 함께 고민합니다.

사용자 피드백과 비즈니스 요구사항을 바탕으로 문제를 정의하고,  
다양한 직군과 협업하며 실제 서비스의 개선을 만들어왔습니다.

- Strong in **Kotlin, Android**
- Interested in **Backend, Cloud Infrastructure**

---

## Experience

### [SK m&service](https://www.skmnservice.com/pc_new/html/main.skmns)
_**2025.07 ~ 2025.09 | Android Engineer Intern, Mobility Business**_
- Built an Android **Mock GPS tool** for TMAP AUTO debugging
- Improved large driving log parsing performance by **50.6%** through buffer tuning, batch processing, and regex simplification
- Designed a **Room-based local caching** structure for offline scenario replay
- Resolved a Compose-WebView rendering issue by adjusting `layoutParams`
- Implemented BLE communication for HUD devices using **Command Queue** and **Big Endian byte transfer**

**Tech**  `Kotlin` `Compose` `Multi-Module` `Build Logic` `Room` `BLE` `Hilt` `JUnit`

### [Ratio](https://trimm.bike/ko)
_**2024.09 ~ 2024.12 | Android Engineer Intern**_
- Developed a **virtual e-bike** app using BLE **GATT Server** for product demo environments
- Replaced `Thread.join()`-based legacy flow with **Coroutines**, reducing UI blocking from **250ms to 0.5ms**
- Ensured stable BLE communication in background with **Foreground Service**
- Built motivation features including **goal setting** and **achievement rate visualization**
- Improved home screen responsiveness by caching data in **Datastore** and updating in the background

**Tech**  `Kotlin` `XML` `Compose` `BLE` `Service` `Coroutine`

### [Sakak](https://www.sakak.co.kr/)
_**2023.06 ~ 2023.08 | Backend Engineer Intern**_
- Development of G-Market Payment Details Parsing API
- Implement MongoDB storage logic by processing unstructured HTML/JSON data to common field criteria
- Verified edge cases with **Pytest-based TDD**
- Experienced pair programming, code review, and collaborative backend development

**Tech**  `Python` `Selenium` `BeautifulSoup` `Flask` `MongoDB`

---

## Main Projects

### [EAT-SSU](https://github.com/EAT-SSU/Android) | [Google Play](https://play.google.com/store/apps/details?id=com.eatssu.android)
_**2023.03 ~ Present | Android Developer / Former Team Leader, PM, AWS Infra Operation**_

A campus meal review service used by **5,000+ users** at Soongsil University.

- Improved **WAU/MAU from 21.8% to 62.4%**
- Built a stable operation workflow with **Crashlytics + Slack**, resolving **15+ major crashes**
- Automated release workflow with **GitHub Actions + Fastlane**
- Solved JWT refresh **Race Condition** with `Mutex`, reducing duplicate refresh attempts to one
- Re-architected legacy code into **MVVM + Clean Architecture**, with gradual **Multi-Module / Compose migration**
- Replaced fragmented `LiveData` states with **sealed UiState**
- Introduced **Firebase Remote Config** to reflect restaurant info changes without app updates
- Built a **Glance widget** and updated menu data in background with **WorkManager**

**Tech**  `Kotlin` `XML` `Compose` `Clean Architecture` `MVVM` `Hilt` `Retrofit` `Coroutine` `Flow` `WorkManager` `Glance` `Firebase` `Fastlane`

### [Saegil](https://github.com/) 
_**2025.03 ~ 2025.07 | Android Developer**_

An AI-based settlement support app for North Korean defectors.

- Reduced voice response latency from **11s to 3s** by switching from REST + TTS flow to **OpenAI Realtime API with WebSocket**
- Reduced unnecessary API calls by **78%** using movement thresholds on map center changes
- Designed the project with **MVVM + Clean Architecture + Multi-Module**
- Built location-based welfare facility features on top of map interactions

**Tech**  `Kotlin` `Compose` `Navigation` `Clean Architecture` `MVVM` `Multi-Module` `Hilt` `Ktor` `Coroutine` `Flow` `Naver Maps` `WebSocket`

### [ISBN Scanner Mini Library](https://github.com/HI-JIN2/isbn-scanner-mini-library)
_**2024.07 | Personal Project**_

An Android-based book registration automation tool built during an overseas volunteer project in Indonesia.

- Automated the flow from **ISBN scan → book lookup → Google Sheets save**
- Reduced registration time per book from **1 minute to 10 seconds**
- Designed the system so non-developers could use it immediately with **Google Sheets as DB**
- Built a working prototype in a constrained field environment

**Tech**  `Kotlin` `ZXing` `Google Books API` `Google Sheets API` `Apps Script`

---

## Awards

- **K-PaaS Digital Social Innovation Contest** — Gold Prize (2nd)
- **AI Online Development Competition Syncathon Season 3** — Grand Prize (2nd)
- **Soongsil University Software Contest** — Gold Prize
- **Soongsil Capstone Design Competition** — Encouragement Prize

---

## Community

### GDSC Soongsil
- Speaker: [학교에서 서비스 운영하기](https://www.youtube.com/watch?v=Qx719VFI6No)
- Speaker: [해외봉사가서 개발하기](https://www.youtube.com/watch?v=BcnWM_nqKow)

### YOURSSU Android
- Developed campus community services and design system projects

### UMC
- Vice Lead of a 50-member university IT club
- Co-hosted the first SSU DEVCON with 6 campus IT clubs and **400 participants**

---

## Education & Certification

- **B.S. in Computer Science**, Soongsil University (2021.03 ~ 2025.08)
- **정보처리기사** (2024.12)
- **SQLD** (2025.12)

---

## Links

- GitHub: https://github.com/HI-JIN2
- Velog: https://velog.io/@jini_1514
- Email: qldls0307@naver.com
