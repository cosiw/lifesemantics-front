# 병원 예약 서비스

## 배포 주소
프론트 서버 : https://web-lifesemantics-front-7e6o2cli373fzh.sel4.cloudtype.app/ <br>
백엔드 서버 : https://port-0-lifesemantics-7e6o2cli373fzh.sel4.cloudtype.app/ <br>
스웨거 : https://port-0-lifesemantics-7e6o2cli373fzh.sel4.cloudtype.app/swagger-ui/index.html#/<br>

## swagger 사용 방법
1. api/login에서 userId와 userPwd를 넣고 Execute를 합니다.
![image](https://github.com/cosiw/lifesemantics-front/assets/91179733/cd6ba023-e724-4563-9083-350a0abce237)

2. 실행해서 생성된 토큰을 저장합니다.
![image](https://github.com/cosiw/lifesemantics-front/assets/91179733/5e5b07da-6794-41a8-bff0-bbd865afc012)

3. Authorization에 저장한 토큰을 붙여넣고 로그인합니다.
![image](https://github.com/cosiw/lifesemantics-front/assets/91179733/afa6c26f-4049-4cee-9f4d-39006ea2ae9a)

4. api를 호출합니다.


## 실행 가이드
### 프론트
```
$ git clone https://github.com/cosiw/lifesemantics-front.git
$ cd lifesemantics-front
$ yarn
$ yarn serve
```

### 백엔드
```
$ git clone https://github.com/cosiw/lifesemantics.git
$ cd lifesemantics
$ ./gradlew build
$ cd build/libs
$ java -jar reservation-0.0.1-SNAPSHOT.jar
```

## ERD
![lifesemantics ERD](https://github.com/cosiw/lifesemantics-front/assets/91179733/07193cc3-9df0-46ec-8f80-6278cd0b3ca4)

