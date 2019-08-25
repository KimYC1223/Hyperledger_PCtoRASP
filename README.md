![image](https://user-images.githubusercontent.com/40852277/63410270-e4a37200-c42d-11e9-934a-b7445aa4daa4.png)

# PC와 RASP 사이의 프라이빗 블록체인 네트워크 구축

### 프로젝트 소개

>2019 한국 항공 대학교 한정희 교수님팀 종합 설계 프로젝트 : 임베디드 환경 기반의 하이퍼레져 패브릭을 이용한 출입 관리 시스템

 본 프로젝트는 기존의 서버 중심으로 운용되던 출입 관리 시스템을 프라이빗 블록체인 네트워크로 구현하여 보안성 측면에서 개선하는 방법을 제시한다. 이번에 사용할 프라이빗 블록체인 엔진인 하이퍼레져 패브릭은, 2018월 3월에 IBM이 1.1버전을 릴리즈한 뒤로 많은 사람들의 사랑을 받고 있는 블록체인 플랫폼이다. 하이퍼레져를 응용한다면 누구든 손쉽게 강력한 보안성을 가지는 네트워크를 구축할 수 있기 때문에, 이번 프로젝트에서도 출입 인증 단말 사이의 네트워크를 구축하기 위해 사용하기로 하였다.

아래 그림은 기존의 서버 중심의 시스템을 보여준다. 사용자들이 자신의 신원을 인증하면, 단말은 서버에 로그를 전송하고 서버는 이를 저장한다.

<br>

![image](https://user-images.githubusercontent.com/40852277/63421925-630b0e80-c444-11e9-9abf-914b08d54112.png)

본 프로젝트에서는 해당 네트워크에 블록체인을 적용 함으로써 변경 불가능성, 비잔틴 장애 허용성, 단일 장애점 제거 등 다양한 보안 이득을 가져갈 수 있음을 보인다. 따라서 다음과 같이 그림 1의 네트워크를 수정한다.

<br><br>

![image](https://user-images.githubusercontent.com/40852277/63649950-5148a480-c77f-11e9-8de2-5a144ec8597d.png)



### 팀원 소개
| 이름 | 학번 | 이메일 | 깃허브 |
|:---:|:---:|:---:|:----:|
| 김영찬 | 2013122041 | kau_esc@naver.com | [KimYC](https://github.com/KimYC1223) |
| 정지원 | 2013122260 | traveloving2030@gmail.com | [traveloving2030](https://github.com/traveloving2030) |
| 이승준 | 2031122201 | scheinbild@naver.com | [scheinbild](https://github.com/scheinbild) |
| 안종화 | 2013122148  | akn0901@naver.com | [ajw0305](https://github.com/ajw0305) |

<br><br><br><br><br><br>

---

![image](https://user-images.githubusercontent.com/40852277/63410197-b0c84c80-c42d-11e9-8aea-c5a1fd892256.png)


# Biuld a private blockchain network between PC and Raspberry PI

### Project introduction

> 2019 Korea Aerospace University Prof.Junghee Han Team Graduation piece : Entrance Management System Using Hyperledger-Fabric Based on Embedded Environment

 This project proposes a method to improve security in terms of implementing the server-centered entrance management system as a private blockchain network. Hyperledger- Fabric, the private blockchain engine used in this readme, is a blockchain platform that has been loved by many people since IBM released version 1.1 in March 2018. Anyone can easily build a strong security network by applying Hyperledger, so we decided to use Hyperledger to build a network between entrance authentication terminals

The following figure shows traditional server-centered system. When user authenticate their identity,  the terminal sends a log to the server, and the server stores them.

<br>

![image](https://user-images.githubusercontent.com/40852277/63421911-5f778780-c444-11e9-9525-5f90640647e3.png)

This project shows that applying the blockchain to the network can bring various security benefits such as immutability, Byzantine fault tolerance(BFT), and eliminate single point of failure. so modify figure 1 network as figure 2

<br><br>

![image](https://user-images.githubusercontent.com/40852277/63649971-76d5ae00-c77f-11e9-99ab-1ff3fcda2c5c.png)


### CONTRIBUTOR

| Name | Student ID | E-Mail | Github Account |
|:---:|:---:|:---:|:----:|
| Kim YoungChan | 2013122041 | kau_esc@naver.com | [KimYC](https://github.com/KimYC1223) |
| Jung JiWon | 2013122260 | traveloving2030@gmail.com | [traveloving2030](https://github.com/traveloving2030) |
| Lee SeungJun | 2031122201 | scheinbild@naver.com | [scheinbild](https://github.com/scheinbild) |
| Ahn JongHwa | 2013122148 | akn0901@naver.com | [ajw0305](https://github.com/ajw0305) |
