🌐 Webbizcraftshop : AWS 기반 SiteBuilder 서비스
---

</br>

### 📍 백엔드 팀원 소개
|                               [김시우](https://github.com/IpekoGosu)                                |                                            [김민우](https://github.com/minwoo1999)                                            |                               [박지호](https://github.com/pjho4746)                                |                               [이종수](https://github.com/leejongsuu)                                |
|:-----------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------:|
|                                       samuelk2873@gmail.com                                        |                                     hmg5959@gmail.com                                      |                                       pjho4746@gmail.com                                        |                                                    tjsdk34549@gmail.com                                                |
| <img src="https://github.com/CloudService-mobile-app/backend/assets/126854628/d628f11a-c30f-408d-9c30-35dc259e6075" width="150" height="150"> | <img src="https://github.com/CloudService-mobile-app/backend/assets/126854628/cfd64afa-d8f8-4d6d-9e3b-e2bf7f5d7ee4" width="150" height="150"> | <img src="https://github.com/CloudService-mobile-app/backend/assets/126854628/1aa8f1cc-cda9-4fa4-b460-1ec802567917" width="150" height="150"> | <img src="https://github.com/CloudService-mobile-app/backend/assets/126854628/eb420fb9-c7c1-4b1c-8762-c86110f53508" width="150" height="150"> |

</br>

### 📍 개요
다양한 콘텐츠로 홍보하고 싶은 기업들을 위한 고객 맞춤형 홈페이지 자동 생성 및 운영 서비스입니다. 

클라우드 기반 플랫폼으로, AWS를 활용하여 손쉽게 고유한 웹사이트를 구축할 수 있습니다.

사용자는 URL을 직접 지정하고 이미지를 업로드하여 자신만의 웹사이트를 생성할 수 있습니다. 또한, 방문자 수, 방문 횟수, 스토리지 용량, 트래픽 등 주요 지표를 실시간으로 모니터링하여 비즈니스 성과를 신속하게 추적할 수 있습니다.

</br>

***※ 보안상의 이유로 코드는 공개되지 않습니다.***

</br>

### 📍 활동
**시작일** <br>
*2024.05.03* <br>

**1차 출시** <br>
*2024.06.14* <br>

***‼️ 20240722 ~ 비활성화***

</br>

---
### 📍 간단 소개
**[기업홈페이지 생성]** <br>
![기업홈페이지 생성](https://github.com/CloudService-mobile-app/backend/assets/126854628/07bdafb5-14bd-40e6-8979-d67991b88342)

**[개별 사용자의 관리 페이지]** <br>
![클라우드 서비스 신청서_모바일앱개발협동조합(수정본v2)_15](https://github.com/CloudService-mobile-app/backend/assets/126854628/e128f044-ba2a-41f1-9f45-0dee5e03fca9)

**[전체 서비스의 관리자 페이지]** <br>
![클라우드 서비스 신청서_모바일앱개발협동조합(수정본v2)_16](https://github.com/CloudService-mobile-app/backend/assets/126854628/62ef9131-9d0a-4fc3-8dc5-42fdf43e6235)

---
### 📍 주요 기능
| **기능**                       | **설명**                                                                                                         |
|--------------------------------|------------------------------------------------------------------------------------------------------------------|
| **자동으로 웹사이트 생성**      | 사용자 요구에 맞춘 구성의 웹사이트를 자동으로 생성합니다. AWS의 S3, Route 53, CloudFront, ACM을 활용하여 동적 도메인을 생성합니다.            |
| **사용자 지정 URL 제공**        | 사용자가 원하는 이름이 포함된 고유한 URL을 생성하여 소개 페이지를 제공합니다. 예를 들어, "goodcompany"라는 이름을 URL에 포함하여 `goodcompany.webbizcraft.shop`과 같은 URL을 제공할 수 있습니다. 사용자는 총 3개의 웹사이트를 생성할 수 있으며, 각 웹사이트는 사용자가 직접 지정하여 고유한 URL을 가질 수 있습니다. |
| **미디어 콘텐츠 업로드**        | 사진, 동영상, 텍스트 등 다양한 콘텐츠를 업로드하여 기업 소개에 활용할 수 있습니다.                                          |
| **트래픽 측정 및 제한**         | 일 단위의 트래픽을 다양한 집계 방식으로 측정하며, Bucket4j와 Redis(Lettuce)를 활용하여 각 웹사이트의 트래픽을 100MB 이하로 제한하여 서버 부하를 관리합니다. 추가 트래픽/용량 요청 시 트래픽/용량을 할당할 수 있습니다. |
| **서버 용량 측정**              | 홈페이지가 서버에서 현재 사용하고 있는 용량을 실시간으로 모니터링하여, 사용자가 데이터를 얼마나 저장하고 있는지 파악할 수 있습니다. AWS CloudWatch를 통해 각 웹사이트의 스토리지 용량을 실시간으로 모니터링합니다. |
| **실시간 트래픽 모니터링 및 알림** | 실시간 트래픽 모니터링을 통해 트래픽이 100MB를 넘으면 알림이 가도록 설정하여 실시간으로 모니터링하고 대응합니다.                                 |
| **전체 관리자 기능 제공**       | Admin 지원으로 쉬운 운영 관리가 가능하며, 트래픽, 용량, 업로드 파일 목록 등의 정보를 일괄적으로 관리합니다. 트래픽 또는 용량이 제한을 초과하면 추가 조치가 필요한 대상들을 자동으로 경고합니다. |
| **추가 트래픽/용량 제공**       | 사용자 요청 시 추가적인 트래픽/용량을 할당할 수 있습니다.                                                                 |
| **개별 사이트 관리**            | 트래픽과 용량 데이터를 사용자가 개별 사이트 관리페이지에서 확인할 수 있습니다. 사용자가 웹사이트를 생성하거나 수정할 때 서비스 관리자의 승인을 받아 지속적인 통합 관리를 지원합니다. |
| **지속적인 통합 관리**          | 사용자가 웹사이트를 생성 또는 수정할 때 서비스 관리자의 승인을 통한 지속적인 통합 관리를 지원합니다.                                          |



</br>

### 📍 결과물
**배포 사이트** <br>
*https://main.webbizcraft.shop* <br>

**시연 영상** <br>
[1차 출시] <br> https://drive.google.com/file/d/1um8aiIWIg_v0zaMoP1ph9c3jFiyG2bNz/view?usp=sharing <br>

</br>

---
### 📍 아키텍쳐 
![모바일앱협동조합 (5)](https://github.com/CloudService-mobile-app/backend/assets/126854628/a0cc2eb7-a7db-46e6-a567-e340f1ea873b)

---

### 📍 사용 기술스택
- SpringBoot
- JPA
- MySQL
- Redis
- AWS
    - EC2
    - S3
    - CloudFront
    - Route53
    - CloudWatch
- Docker
- Bucket4j
- Lettuce
- Nginx
- Jenkins

---

### 📍 사용 라이브러리
- Spring Boot Starter
- JWT
- Swagger
- Firebase
- OkHttp
- QueryDSL
- Lombok
- Jackson
- AWS SDK
    - CloudWatch
    - Route53
    - CloudFront
    - S3
- Database
    - H2
    - MySQL Connector
- Redis
    - Redisson
    - Embedded Redis
    - Bucket4j Core
    - Bucket4j Redis
- Logging
    - Discord Appender

---

### 📍프로젝트 구조
```
└── 🗂 main
    ├── 🗂 java
    │   └── 🗂 com
    │       └── 🗂 example
    │           └── 🗂 cloudservice
    │               ├── 📑 CloudServiceApplication.java
    │               ├── 🗂 auth
    │               │   ├── 🗂 cookie 
    │               │   │   └── 📑 CookieUtil.java
    │               │   ├── 🗂 entity 
    │               │   │   └── 📑 RefreshToken.java
    │               │   ├── 🗂 jwt 
    │               │   │   ├── 📑 JwtAuthenticationFilter.java    
    │               │   │   ├── 📑 JwtAuthorizationFilter.java   
    │               │   │   ├── 📑 JwtProvider.java       
    │               │   │   ├── 📑 MemberDetails.java   
    │               │   │   └── 📑 MemberDetailsService.java   
    │               │   ├── 🗂 repository
    │               │   │   └── 📑 RefreshTokenRepository.java
    │               │   ├── 🗂 service
    │               │   │   └── 📑 RefreshTokenService.java    
    │               │   └── 📑 MemberRole.java           
    │               ├── 🗂 cofig 
    │               │   ├── 🗂 Bucket4j 
    │               │   │   └── 📑 TokenBucketResolver.java 
    │               │   ├── 🗂 CloudWatch 
    │               │   │   └── 📑 CloudWatchConfig.java   
    │               │   ├── 🗂 jpa 
    │               │   │   └── 📑 JpaAuditingConfig.java
    │               │   ├── 🗂 mail 
    │               │   │   └── 📑 MailConfig.java
    │               │   ├── 🗂 RateLimit 
    │               │   │   ├── 📑 RateLimitAspect.java   
    │               │   │   └── 📑 RateLimiterConfig.java     
    │               │   ├── 🗂 redis
    │               │   │   ├── 📑 RedisCacheConfig.java   
    │               │   │   └── 📑 RedisConfig.java   
    │               │   ├── 🗂 redisson
    │               │   │   └── 📑 RedissonConfig.java
    │               │   ├── 🗂 s3
    │               │   │   ├── 📑 awstest.java   
    │               │   │   └── 📑 S3Config.java     
    │               │   ├── 🗂 security
    │               │   │   ├── 📑 SecurityConfig.java   
    │               │   │   └── 📑 SecurityUtils.java   
    │               │   └── 🗂 swagger
    │               │       └── 📑 SwaggerConfig.java  
    │               ├── 🗂 global 
    │               │   ├── 🗂 base 
    │               │   │   └── 📑 BaseTimeEntity.java
    │               │   ├── 🗂 common 
    │               │   │   └── 📑 CommonResDto.java
    │               │   ├── 🗂 dto
    │               │   │   ├── 📑 CommonResponse.java   
    │               │   │   └── 📑 ErrorResponse.java  
    │               │   ├── 🗂 error
    │               │   │   ├── 📑 BucketCapacityException.java 
    │               │   │   ├── 📑 DuplicateAccountException.java 
    │               │   │   ├── 📑 DuplicateUrlException.java           
    │               │   │   ├── 📑 EncryptException.java 
    │               │   │   ├── 📑 FileTooLargeException.java 
    │               │   │   ├── 📑 InvalidTokenException.java   
    │               │   │   ├── 📑 NotFoundAccountException.java 
    │               │   │   ├── 📑 PasswordNotMatchException.java 
    │               │   │   ├── 📑 S3UploadException.java  
    │               │   │   ├── 📑 UnAuthorizedException.java 
    │               │   │   ├── 📑 WebsiteLimitException.java           
    │               │   │   └── 📑 WebsiteNotFoundException.java  
    │               │   ├── 🗂 log
    │               │   │   ├── 📑 FilterConfig.java   
    │               │   │   └── 📑 MDCFilter.java 
    │               │   ├── 📑 ErrorCodes.java  
    │               │   ├── 📑 ErrorResponse.java  
    │               │   ├── 📑 GlobalExceptionHandler.java  
    │               │   └── 📑 GlobalExceptionHandlerFilter.java          
    │               ├── 🗂 member 
    │               │   ├── 🗂 application
    │               │   │   ├── 🗂 dto
    │               │   │   │    ├──📑 MemberResponseDto.java     
    │               │   │   │    └──📑 MemeberRequestDto.java       
    │               │   │   └── 🗂 impl
    │               │   │   │    ├──📑 MailServiceImpl.java     
    │               │   │   │    ├──📑 MemberServiceImpl.java
    │               │   │   │    └──📑 MiddleTableServiceImpl.java      
    │               │   │   ├── 📑 MemberService.java  
    │               │   │   └── 📑 MiddleTableService.java        
    │               │   ├── 🗂 domain
    │               │   │   ├── 🗂 repository
    │               │   │   │    ├──📑 MemberRepository.java     
    │               │   │   │    └──📑 MiddleTableRepository.java   
    │               │   │   ├── 📑 Member.java  
    │               │   │   └── 📑 MiddleTable.java       
    │               │   ├── 🗂 exception
    │               │   │   └── 🗂 dto
    │               │   │        ├──📑 CommonResDto.java     
    │               │   │        └──📑 CommonResponse.java 
    │               │   ├── 🗂 presentation
    │               │   │   └── 📑 MemberController.java
    │               │   ├── 🗂 restapi
    │               │   │   └── 📑 MemberApi.java
    │               │   └── 🗂 utils
    │               │       ├── 📑 MemberScheduler.java
    │               │       └── 📑 MemberUtils.java   
    │               ├── 🗂 visit 
    │               │   ├── 🗂 application  
    │               │   │   └── 🗂 dto
    │               │   │   │    └──📑 VisitResponseDto.java   
    │               │   │   └── 🗂 impl
    │               │   │   │    ├──📑 VisitRedisService.java     
    │               │   │   │    └──📑 VisitServiceImpl.java    
    │               │   │   └── 📑 VisitService.java       
    │               │   ├── 🗂 domain
    │               │   │   ├── 🗂 repository    
    │               │   │   │    ├──📑 VisitRepository.java 
    │               │   │   │    ├──📑 VisitRepositoryImpl.java 
    │               │   │   │    └──📑 VisitRepositoryJPA.java   
    │               │   │   └── 📑 Visit.java    
    │               │   ├── 🗂 exception
    │               │   │   ├── 🗂 dto
    │               │   │   │    ├──📑 CommonResponse.java     
    │               │   │   │    └──📑 RateLimiterException.java 
    │               │   ├── 🗂 presentation
    │               │   │   └── 📑 VisitController.java
    │               │   ├── 🗂 restapi
    │               │   │   └── 📑 VisitApi.java
    │               │   └── 🗂 scheduler
    │               │       └── 📑 VisitScheduler.java
    │               └── 🗂 websiteaa 
    │                   ├── 🗂 application
    │                   │   ├── 🗂 dto
    │                   │   │    ├──📑 WebsiteaaRequestDto.java     
    │                   │   │    └──📑 WebsiteaaResponseDto.java       
    │                   │   └── 🗂 impl
    │                   │   │    └──📑 WebsiteaaServiceImpl.java      
    │                   │   └── 📑 WebsiteaaService.java        
    │                   ├── 🗂 domain
    │                   │   ├── 🗂 repository    
    │                   │   │    └──📑 WebsiteaaRepository.java   
    │                   │   ├── 📑 Template.java  
    │                   │   └── 📑 Websiteaa.java       
    │                   ├── 🗂 exception
    │                   │   └── 🗂 dto
    │                   │        └──📑 CommonResponse.java 
    │                   ├── 🗂 presentation
    │                   │   └── 📑 WebsiteaaController.java
    │                   ├── 🗂 restapi
    │                   │   └── 📑 WebsiteaaApi.java
    │                   └── 🗂 utils
    │                       │── 📑 MultipartJackson2HttpMessageConverter.java   
    │                       │── 📑 WebsiteaaEnums.java         
    │                       └── 📑 WebsiteaaUtils.java 
    └── 🗂 resources
         └── 🗂 scripts   
         │   ├── 📑 getVisitCounts.lua
         │   └── 📑 incrementVisitCount.lua   
         └── 🗂 temlates   
         │   ├── 📑 bizcraft_logo.png
         │   └── 📑 email-template.html          
         ├── 📑 application.yaml      
         ├── 📑 application-dev.yml      
         ├── 📑 application-local.yml      
         ├── 📑 application-prod.yml  
         ├── 📑 application-test.yml
         └── 📑 logback.xml  
                                        
```
---

### 📚 학습 성과

### 방문 도메인 최적화

방문 도메인의 기능을 개선하기 위해 기존의 데이터베이스 기반 시스템에서 Redis와 Scheduler를 활용한 새로운 아키텍처를 도입했습니다. 이로 인해 실시간으로 변동하는 데이터를 보다 효율적으로 처리하고, 시스템 성능을 크게 향상시킬 수 있었습니다.

</br>

#### 기존 DB 시스템에서 Redis로 전환한 이유

기존 시스템에서는 방문 데이터를 데이터베이스에 직접 저장하고 조회하는 방식으로 처리했습니다. 그러나 이러한 방식은 다음과 같은 한계점이 있었습니다:

1. **성능 저하**: 실시간으로 변동하는 방문 데이터를 DB에 저장하고 조회하는 과정에서 I/O 성능 저하가 예상되었고, 특히 트래픽이 많은 시점에서는 지연이 발생할 수 있었습니다.
2. **확장성의 한계**: DB는 대량의 동시 요청을 처리하는 데 있어 한계가 있으며, 성능을 유지하기 위해서는 추가적인 자원 할당이 필요했습니다.

</br>

이러한 문제를 해결하기 위해 저는 Redis를 도입했습니다. Redis는 메모리 기반의 데이터 저장소로서, 매우 빠른 읽기/쓰기 속도를 제공하며, 특히 실시간 데이터 처리에 적합합니다. 뿐만 아니라, Redis는 클러스터링을 통해 손쉽게 확장할 수 있어 대규모 트래픽을 처리하는 데도 유리했습니다. 이러한 이유로, Redis를 도입하여 실시간 데이터를 인메모리에서 처리하도록 시스템을 개선했습니다. 이 전환을 통해 성능 문제를 해결하는 동시에 시스템의 확장성도 크게 향상시킬 수 있었습니다.

</br>

#### Lua 스크립트 도입

Redis 도입 이후, 성능을 최적화하고 데이터 처리 효율성을 높이기 위해 Lua 스크립트를 추가적으로 활용했습니다. 제가 Lua 스크립트를 사용한 이유는 다음과 같습니다:

1. **통신 효율화**: Redis와의 통신을 최소화하기 위해, 여러 명령어를 하나의 Lua 스크립트로 묶어 한 번의 요청으로 처리했습니다. 이를 통해 네트워크 오버헤드를 줄이고, 응답 시간을 단축할 수 있었습니다.
2. **원자적 실행 보장**: Lua 스크립트는 여러 Redis 명령어를 원자적으로 실행할 수 있어, 데이터 일관성을 유지하는 데 큰 도움이 되었습니다. 이는 복잡한 데이터 연산이 필요한 상황에서도 데이터 무결성을 보장합니다.
3. **경량성과 비용 절감**: Lua 스크립트는 매우 경량이므로, Redis의 인메모리 특성과 결합하여 시스템 리소스 사용을 최적화할 수 있었습니다. 이로 인해 전체적인 시스템 운영 비용을 절감할 수 있었습니다.

이러한 기술들을 활용하여, 성능이 최적화되고 데이터 일관성이 유지되는 방문/방문자 수 측정 기능을 구현할 수 있었습니다. 또한, 단순 조회 작업에는 **@Cacheable**을 활용하여 시스템의 복잡성을 줄이면서도 성능을 극대화했습니다.

</br>

#### Scheduler 도입

실시간 데이터 처리를 최적화하기 위해 **Scheduler**를 도입하였습니다. 기존의 Batch 작업과 비교하여 Scheduler를 선택한 이유는 다음과 같습니다:

- **실시간 데이터 처리**: Batch 작업은 주기적으로 대량의 데이터를 처리하는 데 적합하지만, 실시간성을 요구하는 데이터에서는 지연이 발생할 수 있습니다. Scheduler는 일정한 간격으로 데이터를 처리하므로, 실시간 데이터 처리에 더 유리합니다.
- **효율적인 자원 관리**: Scheduler는 필요에 따라 작업을 수행하므로, 자원을 보다 효율적으로 사용할 수 있습니다. 이는 특히 트래픽이 변동하는 환경에서 시스템의 안정성을 유지하는 데 도움이 됩니다.
- **유연성**: 다양한 작업 스케줄링 옵션을 제공하여, 시스템의 특성에 맞게 최적의 작업 주기를 설정할 수 있습니다. 이를 통해 성능과 효율성을 모두 확보할 수 있었습니다.

이와 같은 기술적 선택과 최적화 전략을 통해, 방문 도메인 최적화 기능을 성공적으로 구현할 수 있었습니다. 이를 통해 성능이 크게 향상되었으며, 데이터 일관성을 유지하면서도 실시간 데이터 처리의 효율성을 극대화할 수 있었습니다.

</br>

### 클라우드 인프라 구축 및 모니터링 경험

이번 프로젝트에서 저는 **AWS**의 다양한 서비스를 활용해 클라우드 인프라를 구축하고 운영하면서, 클라우드 환경에 대한 깊은 이해를 쌓게 되었습니다. 이 과정은 단순한 기술 도입을 넘어, 클라우드 기반 시스템의 복잡성을 이해하고 관리하는 중요한 경험이었습니다.

#### 동적 도메인 및 콘텐츠 배포

프로젝트 초기, 글로벌 사용자에게 빠르고 안정적인 콘텐츠를 제공하는 것이 중요한 과제였습니다. 이를 해결하기 위해 저는 **S3, Route 53, CloudFront, ACM**을 활용한 동적 도메인 설정과 콘텐츠 배포 시스템을 구축했습니다. 이 시스템을 통해 전 세계 사용자들에게 일관된 경험을 제공할 수 있었고, 콘텐츠 전달 속도도 크게 향상시켰습니다. 이 경험을 통해 클라우드 인프라의 유연성과 확장성을 체감할 수 있었습니다.

#### 실시간 모니터링 및 자원 관리

클라우드 환경에서 실시간 모니터링은 시스템의 안정성을 유지하는 데 필수적입니다. 저는 **AWS CloudWatch**를 활용하여 트래픽과 자원 사용량을 실시간으로 모니터링하고, 필요 시 즉시 대응할 수 있는 시스템을 구축했습니다. 예를 들어, 갑작스러운 트래픽 증가로 인한 자원 부족을 예방하기 위해 용량 제한을 설정하고, 적절한 시점에 자원을 확장함으로써 시스템의 안정성을 유지할 수 있었습니다.

#### 트래픽 및 용량 최적화

프로젝트가 진행될수록, 실시간 트래픽 분석과 관리는 시스템 성능 최적화의 핵심 요소로 떠올랐습니다. 저는 지속적인 모니터링과 데이터를 기반으로 시스템을 최적화하는 방법을 터득했습니다. 이를 통해 시스템의 성능과 안정성을 높이는 동시에, 불필요한 자원 낭비를 줄일 수 있었습니다.

---

이 프로젝트를 통해, 클라우드 인프라의 구축과 관리에 대한 깊은 이해를 얻었고, 특히 자원의 효율적 사용과 비용 관리의 중요성을 실감하게 되었습니다. 앞으로도 이러한 경험을 바탕으로 클라우드 환경에서의 최적화 작업에 적극적으로 기여할 수 있을 것입니다.


