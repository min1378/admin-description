# Admin 메뉴 설명서

아래는 **Admin 권한**으로 접근 가능한 주요 메뉴들의 설명입니다.

## 📋 목차

- [회원 관리](#회원-관리)
- [상품 관리](#상품-관리)
- [카테고리 관리](#카테고리-관리)
- [주문 관리](#주문-관리)
- [주문 상세 / 품목 관리](#주문-상세--품목-관리)
- [상품 통계](#상품-통계)
- [데이터 동기화](#데이터-동기화)
- [강사 계정 관리](#강사-관리)
---






## 👤 회원 관리
![image](https://github.com/user-attachments/assets/c4e723bf-285a-4202-ba4d-115e4da7d65f)

- **/members** 경로에서 모든 회원 리스트를 확인할 수 있습니다.
- 이름, 이메일, 가입일자 등의 정보가 표시됩니다.
- 상세 조회 시 회원이 주문한 정보를 확인할 수 있습니다.
  ![image](https://github.com/user-attachments/assets/8f0cc4f1-2bbf-441a-ac6b-499148a4b70e)


---

## 🛒 상품 목록
![image](https://github.com/user-attachments/assets/81adc099-fe0b-4ac6-a6c4-65a1e854a7d0)

- **/products** 경로에서 등록된 모든 상품을 조회합니다.
- 카테고리별 필터링이 가능하며, 이름으로 검색이 가능합니다.
- 상품을 클릭하면 해당 상품과 관련된 정보를 확인할 수 있습니다.
  ![image](https://github.com/user-attachments/assets/fa9299b8-05db-467c-8893-cd840b4a3ce2)

### 상품 상세
- 상품 상세 페이지에서는 상세 / 수강생 / 주문 목록 / 월별 주문 금액을 확인할 수 있습니다.
  ![image](https://github.com/user-attachments/assets/499e4716-05a9-43c8-981c-ffbbf1535231)
  ![image](https://github.com/user-attachments/assets/25c4e3dc-d911-4ecc-9858-aa913a1af400)
  ![image](https://github.com/user-attachments/assets/f5a2fadf-8533-4fdc-9065-088b368e4d97)
  ![image](https://github.com/user-attachments/assets/abf26a85-826a-4ad4-b82e-d4169cd9bee7)




---

## 🗂 상품 카테고리

- **/categories** 경로에서 상품 카테고리를 관리할 수 있습니다.
- 현재 카테고리 종류와 관련된 상품을 확인할 수 있습니다.
  ![image](https://github.com/user-attachments/assets/c531f24d-bc16-423f-bfc6-8971cfe3142c)
- 상품 보기를 누르면 해당 카테고리에 연결된 상품을 확인할 수 있습니다.
  ![image](https://github.com/user-attachments/assets/c534abef-6b7e-43a3-975f-08f11f7e67f0)



---

## 📦 주문 관리
![image](https://github.com/user-attachments/assets/6e7650a7-e762-49a0-b208-1e8a5220bca5)
- 주문 별로 데이터를 확인할 수 있습니다.
- export를 누르면 엑셀(csv)로 다운로드 가능합니다.
- 주문을 클릭해 상세 주문을 확인할 수 있고 관련된 상품을 확인할 수 있습니다.
  ![image](https://github.com/user-attachments/assets/5662a758-f2bc-43c0-80f6-f0f232c8329b)

---


## 📊 상품별 주문 현황

- **/products/order-stats** 에서 상품별 주문 건수와 매출 합계를 조회할 수 있습니다.
![image](https://github.com/user-attachments/assets/ee4f79d4-53dc-4ffa-8f39-8138b9aca339)

---

## 🔄 데이터 동기화
![image](https://github.com/user-attachments/assets/e2c42abf-71d4-4514-8a49-2de2c63c1901)

- **/sync** 우측 상단 동기화 버튼을 클릭해 다음 데이터를 동기화할 수 있습니다:
  - 카테고리
  - 상품
  - 회원
  - 주문
  - 주문 품목
- imweb에서 데이터를 받아오는 것이기 때문에 데이터가 보이지 않는다면 버튼을 누르면 동기화할 수 있습니다.
- 자주 누르면 imweb에서 비정상적인 요청으로 취급되어 1분에 한번 부탁드립니다.
---

## 강사 계정 관리
![image](https://github.com/user-attachments/assets/920a070f-d88c-43a0-94fa-93455eda274b)
- 강사 계정을 관리할 수 있는 페이지입니다.
- Create 버튼을 클릭해 강사 계정을 생성할 수 있습니다.

### 강사 계정 생성
![image](https://github.com/user-attachments/assets/662acf23-dc37-49c9-908a-a0c9cf71d33e)
강사에 필요한 필수값들을 입력해야 계정을 생성할 수 있습니다.

### 강사 상세 정보
![image](https://github.com/user-attachments/assets/fa4c4441-4d67-45ed-a4d8-0095ed9d01d2)

- 강사 정보와 강사에 연결된 강의 정보를 확인할 수 있고 강의 월별 차트도 확인할 수 있습니다.

#### 강의 연결하기
- 강의 연결하기 버튼을 누르면 다음과 같은 모달 창이 나타납니다.
  ![image](https://github.com/user-attachments/assets/37ec9634-401e-40fc-b0b7-6095c25758e4)
- 강의들을 체크한 후 연결 버튼을 눌러 강사와 상품을 연결할 수 있습니다.
  

> 본 문서는 관리자(Admin) 권한을 가진 사용자만 접근 가능한 메뉴를 기준으로 작성되었습니다.
