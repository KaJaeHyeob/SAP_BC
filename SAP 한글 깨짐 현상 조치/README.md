# SAP 한글 깨짐 현상 조치

<details>
<summary>목차 및 링크</summary>
<div markdown="1">

> [1. 개요]()    
> [2. 해결방법]()    
> > [1) SAP Logon 실행]()    
> > [2) 대상 시스템 우클릭 및 속성 메뉴 클릭]()    
> > [3) 코드 페이지 탭 클릭 및 인코딩 포맷 UTF8 변경]()    

</div>
</details>

## 1. 개요

 SAP ERP 제품을 사용하다 보면 데이터를 다운로드 및 업로드하는 여러 과정에서 한글이 깨지는 현상이 나타난다. 이는 SAP GUI가 데이터를 출력할 때 사용자가 지정한 인코딩 포맷으로 변환하여 출력하기 때문이다. 따라서, 인코딩 포맷만 알맞게 변경해주면 간단하게 해결할 수 있다.    
 SAP GUI 설정은 글로벌 설정과 시스템별 설정으로 나뉘는데 인코딩은 시스템별로 설정 가능하다.    

## 2. 해결방법

### 1) SAP Logon 실행

![Untitled](/image/Untitled.png)

- SAP GUI 시스템별 설정을 위해 시스템 목록을 조회할 수 있는 SAP Logon 프로그램을 실행한 것이고, 글로벌 설정은 SAP GUI Configuration 프로그램에서 가능하다.    

### 2) 대상 시스템 우클릭 및 속성 메뉴 클릭

![Untitled](/image/Untitled.png)

### 3) 코드 페이지 탭 클릭 및 인코딩 포맷 UTF8 변경

![Untitled](/image/Untitled.png)
