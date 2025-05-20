🌐 Webbizcraftshop : AWS 기반 SiteBuilder 서비스
---

***※ 보안상의 이유로 코드는 공개되지 않습니다.***

</br>

### 📍 개요
다양한 콘텐츠로 홍보하고 싶은 기업들을 위한 고객 맞춤형 홈페이지 자동 생성 및 운영 서비스입니다. 

클라우드 기반 플랫폼으로, AWS를 활용하여 손쉽게 고유한 웹사이트를 구축할 수 있습니다.

사용자는 URL을 직접 지정하고 이미지를 업로드하여 자신만의 웹사이트를 생성할 수 있습니다. 또한, 방문자 수, 방문 횟수, 스토리지 용량, 트래픽 등 주요 지표를 실시간으로 모니터링하여 비즈니스 성과를 신속하게 추적할 수 있습니다.

</br>

### 📍 활동
*2024.05.03 ~ 2024.07.22*

</br>

### 📍 간단 소개
**[기업홈페이지 생성]** <br>
![기업홈페이지 생성](https://github.com/user-attachments/assets/de4cd25d-922d-420e-9b0a-819e691c59ce)

</br>

**[개별 사용자의 관리 페이지]** <br>
![클라우드 서비스 신청서_모바일앱개발협동조합(수정본v2)_15](https://github.com/user-attachments/assets/5213fa5c-f242-43ed-8264-1d062e57719d)

</br>

**[전체 서비스의 관리자 페이지]** <br>
![클라우드 서비스 신청서_모바일앱개발협동조합(수정본v2)_16](https://github.com/user-attachments/assets/62889eed-5c36-444a-92e4-df5cf56beef7)

</br>

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

### 📍 아키텍쳐 
![모바일앱협동조합 (5)](https://github.com/user-attachments/assets/76ebb865-bc47-4a5b-a1fe-e5836616073f)

</br>

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

</br>

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

</br>

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
