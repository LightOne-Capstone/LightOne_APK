# LightOne_APK
- LIGHT HOUSE APK (Version 1)
1. AI
- Python
- Requests 기반을 이용하여 PDF를 불러옴
- Konlpy 패키지를 사용하여 PDF 내 데이터를 토큰화
- KoBART 모델을 사용하여 내용 요약
- 정규표현식을 사용하여 문서 내 특성 추출

2. API 서버
- Python
- FastAPI를 이용하여 Swagger를 동반한 API 제공
- Docker 및 Jenkins를 통해 지속적 배포

3. Android 클라이언트
- Kotlin
- MVVM 아키텍쳐 패턴
Jetpack Navigation, Safe args 를 이용한 Fragment 개발
Room DB 라이브러리를 이용한 내장 DB활용
Koin 라이브러리를 통한 의존성 관리
