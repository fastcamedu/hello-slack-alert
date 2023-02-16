# 저장소 설명
슬랙을 이용한 중요 에러 알림 샘플 프로젝트

## 강의 정보
| 분류    | 강의명                          |
|-------|------------------------------|
| 강의명   | 초간단 이커머스 서비스에서 대규모 서비스로 도약하기 |
| 파트 01 | 스타트업 초기 서비스 개발               |
| 챕터 10 | 초간단 이커머스 서비스 알람 구축           |
| 클립 02 | Slack을 이용한 알람 서비스            |

### 필수 의존성
```groovy
dependencies {
    implementation 'org.springframework.boot:spring-boot-starter-web'
    implementation 'com.slack.api:slack-api-client:1.27.2'
}
```