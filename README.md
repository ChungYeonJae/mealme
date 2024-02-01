# ✔ MEALME
### 먹은 음식을 기록하고 기록한 식단을 분석해 전문가에게 상담할 수 있는 공간
식단 기록, 관리, 컨설팅, 상품 구매까지 한번에 이용할 수 있는 사이트
  
</br>
</br>

# ✔ 개발 기간
### 2023.06.24 ~ 2023.07.24  
</br>
</br>

# ✔ 팀 구성 
| 구성  | 6인  |  작업 목록  |
| :---: | :---: | :---: |
| 팀장 | 이재우 | 회원가입, 로그인, 식단 작성, 작성 리스트 |
| 부팀장 | 이동재 | 관리자 |
| **팀원** | **정연재** | **전문가 선택** |
| 팀원 | 유정현 | 상담 |
| 팀원 | 김예슬 | 오늘 하루, 차트(일간,주간,월간), 리뷰(식단상담, 상품구매) |
  
</br>
</br>
  
# ✔ Stacks (SpringBoot Project) 
|   |   |
| :--- | :--- |
| 💻 IDE | ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)  ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)  |  
| 📋 Language | ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)  |
| ⚙️ Framework | ![SpringBoot](https://img.shields.io/badge/SpringBoot-%236DB33F.svg?style=for-the-badge&logo=SpringBoot&logoColor=white)  ![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=for-the-badge&logo={MyBatis}&logoColor={black}) |
| 📚 Library | ![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white) |
| 💾 Database | ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white) |
| 🗄️ Server | ![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black) |  
| 📤 Version Control | ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) |
  
</br>
</br>

# 작업 목록
- ## ✨컨설팅 신청
- ### 기관 선택
- #### 1) 회원이 컨설팅을 신청 할 전문가 카테고리 선택하기 (병원, 트레이너, 영양사)
- #### 2) 페이지 이동 queryString을 이용해 부여한 번호에 따라 해당 목록에 맞는 리스트들을 제공하기
- ### 세부사항 검색
- #### 1) 회원이 선택 한 카테고리의 전문가 리스트를 보여주기(별점, 회사명, 대표자 명, 대표사진, 대표전화, 주소)
- #### 2) 고객들이 리뷰 작성 시 부여하는 별점을 종합하여 평균 별점을 보여주기
- #### 3) 페이징 처리를 하여 더 많은 전문가들을 볼 수 있음(th태그를 사용 해 each문을 돌리고 색깔 변환은 ajax로 처리)
- ### 상세 정보 보여주기
- #### 1) 회원이 선택 한 전문가의 상세 정보 보여주기(별점, 회사명, 대표자 명, 대표사진, 대표전화, 사업자 번호, 홈페이지, 이메일, 한 줄 소개글, 주소, 위치약도)
- #### 2) 해당 전문가의 상세정보를 불러오기 위해 queryString을 사용 함
- #### 3) 지도 api를 사용 해 주소에 맞는 위치를 지도로 상세하게 안내해주기
- #### 4) 하단에 고객들이 작성 한 리뷰와 별점들을 보여주고 페이징 처리를 하여 더 많은 리뷰들을 볼 수 있게
- ### 컨설팅 신청하기
- #### 1) 해당 전문가가 마음에 들어 회원이 컨설팅 신청하기
- #### 2) 신청하기 버튼 클릭 컨설팅 페이지로 이동(queryString을 이용하여 해당 전문가의 기업번호와 고객번호를 컨설팅 페이지로 넘겨줌)
- #### 3) 날짜를 선택 해 해당 날짜에 포함하는 식단을 불러 옴(날짜 선택에는 datePicker 사용)
- #### 4) 추가적으로 전문가에게 하고 싶은 말 작성하기(summerNote 사용)
- ### 결제하기
- #### 1) 신청 한 컨설팅에 대한 비용 결제하기
- #### 2) 결제하기 버튼 클릭 시 카카오페이로 결제(아임포트와 카카오페이 api 사용)
- #### 3) QR코드를 핸드폰으로 스캔 후 카카오페이로 결제하기
- #### 4) 결제가 완료되면 자동으로 결제 완료 페이지로 이동 함
- ### 겔제완료 페이지
- #### 1) 주문내역 페이지로 이동해 본인이 신청한 컨설팅 내역들을 확인하기
- #### 2) 주문내역을 확인하지 않을 시 메인 페이지로 이동하기 버튼 클릭
