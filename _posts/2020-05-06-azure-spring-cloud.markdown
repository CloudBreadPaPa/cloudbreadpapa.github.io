---
layout: post
title:  "클라우드로 관리되는 Java 기반 spring 서비스 - azure spring cloud"
description: Azure의 Spring Cloud를 사용하여 Spring boot 앱을 개발
date:   2020-05-06 09:00:00 +0900
categories: microsoft azure java spring cloud
---

# About - Spring boot에 대해
국내에서 가장 많이 사용하는 Java 개발자들에게 Spring 프레임워크를 그대로 활용해 클라우드에 쉽게 배포가 가능 - 2020년 5월 6일 현재 preview 단계
- [Microsoft + Pivotal](https://azure.microsoft.com/ko-kr/overview/linux-on-azure/pivotal/#features)
- [2019년 Azure Spring Cloud 공식발표](https://azure.microsoft.com/en-us/blog/introducing-azure-spring-cloud-fully-managed-service-for-spring-boot-microservices/)
- [리눅스 on Microsoft Azure](https://azure.microsoft.com/en-us/overview/linux-on-azure/)
- [Spring on Azure 소개 슬라이드](https://www.slideshare.net/Pivotal/azure-spring-cloud)
![]({{site.url}}/assets/images/202005/2020-05-06-105858.png)

# Trend
- Spring, Spring/Boot 프레임워크 56% 이상 점유율
![]({{site.url}}/assets/images/202005/2020-05-06-105856.png)
(참고링크 : https://www.jetbrains.com/lp/devecosystem-2019/java/)

# Azure Srping Cloud 장점
[Azure Spring Cloud](https://docs.microsoft.com/en-us/azure/spring-cloud/spring-cloud-overview)의 장점
- Fully managed​
infrastructure​
- Built-in app lifecycle management​
- Ease of monitoring

```
Azure Spring Cloud makes it easy to deploy Spring Boot-based microservice applications to Azure with zero code changes. 
```
- "zero code changes" 부분이 주목할 부분
- Java + micro-service 개발에 대한 손쉬운 접근을 제공
- DevOps / 클라우드 storage 및 모니터링 통합

# Developer value - 개발 과정
[spring cloud 배포 및 실행 가이드](https://docs.microsoft.com/en-us/azure/spring-cloud/spring-cloud-quickstart-launch-app-cli) 문서를 참조해 테스트 수행

## github에 올라온 트레이닝 가이드 문서
[github 트레이닝 문서](https://github.com/microsoft/azure-spring-cloud-training)
- workshop 수준의 가이드 제공

# Closing
- 튜토리얼 가이드 문서만 수행해도 충분히 지행 패턴에 대한 이해 가능해서 좋음
- 클라우드 기반 스케일링 역시 쉽게 가능
- 모니터링 부분도 만족
- DevOps 부분은 위의 [github 트레이닝 가이드](https://github.com/microsoft/azure-spring-cloud-training) 내용을 더 봐야 할 듯