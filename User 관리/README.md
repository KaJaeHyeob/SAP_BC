# User 관리

<details>
<summary>목차 및 링크</summary>
<div markdown="1">

> [1. 개요](https://github.com/KaJaeHyeob/SAP_BC/tree/master/SAP%20ERP%20User%20%EA%B4%80%EB%A6%AC#1-%EA%B0%9C%EC%9A%94)    
> [2. 업무 매뉴얼](https://github.com/KaJaeHyeob/SAP_BC/tree/master/SAP%20ERP%20User%20%EA%B4%80%EB%A6%AC#2-%EC%97%85%EB%AC%B4-%EB%A7%A4%EB%89%B4%EC%96%BC)    
> > [1) User 목록 확인](https://github.com/KaJaeHyeob/SAP_BC/tree/master/SAP%20ERP%20User%20%EA%B4%80%EB%A6%AC#1-user-%EB%AA%A9%EB%A1%9D-%ED%99%95%EC%9D%B8)    
> > [2) User 정보 확인 및 수정](https://github.com/KaJaeHyeob/SAP_BC/tree/master/SAP%20ERP%20User%20%EA%B4%80%EB%A6%AC#2-user-%EC%A0%95%EB%B3%B4-%ED%99%95%EC%9D%B8-%EB%B0%8F-%EC%88%98%EC%A0%95)    
> > [3) User 생성](https://github.com/KaJaeHyeob/SAP_BC/tree/master/SAP%20ERP%20User%20%EA%B4%80%EB%A6%AC#3-user-%EC%83%9D%EC%84%B1)    
> > [4) User 복사 생성](https://github.com/KaJaeHyeob/SAP_BC/tree/master/SAP%20ERP%20User%20%EA%B4%80%EB%A6%AC#4-user-%EB%B3%B5%EC%82%AC-%EC%83%9D%EC%84%B1)    
> > [5) User 잠금 설정 및 해제](https://github.com/KaJaeHyeob/SAP_BC/tree/master/SAP%20ERP%20User%20%EA%B4%80%EB%A6%AC#5-user-%EC%9E%A0%EA%B8%88-%EC%84%A4%EC%A0%95-%EB%B0%8F-%ED%95%B4%EC%A0%9C)    
> > [6) User 삭제](https://github.com/KaJaeHyeob/SAP_BC/tree/master/SAP%20ERP%20User%20%EA%B4%80%EB%A6%AC#6-user-%EC%82%AD%EC%A0%9C)

</div>
</details>

-----

## 1. 개요    

 하나의 SAP ERP System 안에서 조직적 단위는 Client로 나뉘고, 하나의 Client는 여러 User로 구성된다.    
 먼저 간단하게 Client와 User에 대해서 설명한 후, User 관리에 대한 업무 매뉴얼을 살펴보도록 하겠다.
 
 이미지
 
 위의 그림과 같이 Client는 세 자리 숫자로 구성된 Client Number로 식별하고, User는 알파벳+숫자로 이루어진 User ID로 식별한다.    
 Client는 서로 독립적인 조직이기 때문에, 위 그림에서 Client01(100)의 User01과 Client02(200)의 User01이 같은 User ID를 갖더라도 완벽히 다른 User로 구별된다.    
 
 이미지
 
 위의 그림과 같이 User는 자신이 속한 Client의 Client Number와 자신의 User ID를 사용하여 SAP ERP에 접속한다.    

-----

## 2. 업무 매뉴얼

### 1) User 목록 확인    

 현재 접속 중인 Client에 어떤 User가 포함되어있는지 확인하기 위해선 T-code SUIM을 사용하면 된다. SUIM에서는 User 목록, Role 및 Profile 등의 권한 목록, T-code 목록 등을 확인할 수 있다.    
 
![Untitled](./image/Untitled.png)

![Untitled1](./image/Untitled1.png)

![Untitled2](./image/Untitled2.png)

![Untitled3](./image/Untitled3.png)

 위와 같은 방법으로 SUIM에서 User 목록을 확인할 수 있으며, 앞으로의 업무 매뉴얼 작성은 107220001이라는 User ID를 가진 테스트 계정을 사용하여 진행할 것이다.    

### 2) User 정보 확인 및 수정

 User 관리의 대부분은 T-code SU01에서 이루어진다. 가장 먼저 특정 User의 정보를 확인하고 수정하는 방법에 대해서 알아보겠다.    

![Untitled4](./image/Untitled4.png)

![Untitled5](./image/Untitled5.png)

![Untitled6](./image/Untitled6.png)

![Untitled7](./image/Untitled7.png)

![Untitled8](./image/Untitled8.png)

![Untitled9](./image/Untitled9.png)

![Untitled10](./image/Untitled10.png)

![Untitled11](./image/Untitled11.png)

![Untitled12](./image/Untitled12.png)

![Untitled13](./image/Untitled13.png)

### 3) User 생성

![Untitled14](./image/Untitled14.png)

![Untitled15](./image/Untitled15.png)

![Untitled16](./image/Untitled16.png)

![Untitled17](./image/Untitled17.png)

![Untitled18](./image/Untitled18.png)

### 4) User 복사 생성

![Untitled19](./image/Untitled19.png)

![Untitled20](./image/Untitled20.png)

![Untitled21](./image/Untitled21.png)

![Untitled22](./image/Untitled22.png)

![Untitled23](./image/Untitled23.png)

![Untitled24](./image/Untitled24.png)

### 5) User 잠금 설정 및 해제

![Untitled25](./image/Untitled25.png)

### 6) User 삭제

![Untitled26](./image/Untitled26.png)
