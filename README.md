![](https://velog.velcdn.com/images/chan9708/post/25cd22f6-5f13-4685-960a-cec718175498/image.png)

>
[docker-app-handsout](https://github.com/ChanLim-BD/docker-app-handsout)

---
## App 개요
---
![](https://velog.velcdn.com/images/chan9708/post/fe9c1616-333d-4b3d-a80b-49ab0ea78b0b/image.JPG)

* React와 Node.js를 이용한 간단한 Full Stack 프로그램입니다.
> 
클라이언트에 글을 입력을 하면 리액트를 통해서 노드로 전달된 이후 MySQL 데이터베이스에 저장한 후, 그 저장된 것을 화면에 보여주는 애플리케이션입니다.
그리고 컨테이너를 재시작해도 DB에 저장된 데이터는 남아있게 해줄 것입니다.

* 애플리케이션 개발이 중점을 두지 않습니다.
* 목적은 **Front/Back-end**가 구현된 **FullStack** 애플리케이션 즉, **Multi Container 앱**을 Docker로 이용하여 구동합니다.
* Github에 배포 후 자동으로 Travis가 호출하여 CI를 진행합니다.
* Travis에서의 과정이 끝나면 AWS ElasticBeanstalk가 배포합니다.

---

## Development Environment

![](https://velog.velcdn.com/images/chan9708/post/6d76b359-75f9-4ae1-acd5-2615f519aa6c/image.jpg)

- React
- Node.js
- MySQL
- Docker
- NGINX
- Travis
- AWS ElasticBeanstalk

---

## Flowchart

![](https://velog.velcdn.com/images/chan9708/post/ca8519c4-e29c-4b8a-ab41-218456480cb2/image.JPG)

![](https://velog.velcdn.com/images/chan9708/post/50b4912f-188e-4535-8b1a-d63e0d20a517/image.png)

: Nginx로 클라이언트에서 오는 요청을 백엔드 서버와 프론트 서버로 나눠주는 구조입니다.

---

## Shots
![](https://velog.velcdn.com/images/chan9708/post/1ead144e-95e9-43e5-a104-b2bbc0ef0c3b/image.JPG)

![](https://velog.velcdn.com/images/chan9708/post/4d28e1e5-215d-4d59-98e9-c5e809e88e21/image.JPG)


(현재는 AWS 다 중단.)

![](https://velog.velcdn.com/images/chan9708/post/943b6bc2-5c52-46db-b599-fa02f750f2d9/image.JPG)

* RDS

![](https://velog.velcdn.com/images/chan9708/post/39ed85ad-5a39-4e15-9d55-e95e9009126f/image.JPG)

* Travis CI 구동 확인

---

# Reference
>
[따라하며 배우는 도커와 CI환경](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-%EB%8F%84%EC%BB%A4-ci/dashboard)


