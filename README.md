# 미니프로젝트 humancloud - 이력서 관리 웹 사이트

### 개발 이유
 1. 평생직장이 없어지는 추세에 따라 이력관리 사이트의 필요성을 느낌
 2. 구직자는 원하는 기업을 구직자는 원하는 스팩의 인재를 빠르게 찾을 수 있게 하는 공간을 마련하기 위함
 
### 벤치마크 
 ![image](https://user-images.githubusercontent.com/108394995/210055394-ce885ee2-d47d-4207-8a79-2210ffaba25b.png)
 ![image](https://user-images.githubusercontent.com/108394995/210055406-7a7236f8-02ec-4416-9fdf-94f4ac8bb3da.png)

- 구직자와 기업간의 매칭 사이트를 구현하기 위해서 두 사이트를 참고
- 사람인은 모든 종류의 직업에 대해서, 원티드는 개발자 직군의 매칭을 위주로 함
- 개발자를 위한 매칭 사이트가 목표였으므로 원티드를 메인으로 설계

### 테이블 구성

![Untitled](https://user-images.githubusercontent.com/108394995/210054811-847039dd-2224-4ace-ae97-26af7b3b81f3.png)

### 1. 제작 기간
2022.10.05 ~ 2022.10.19


### 2. 개발 환경

* Tool ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) 

* FrontEnd ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

* BackEnd ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white) 
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) 
![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white) 
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)

* Team 	![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) ![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)

### 3. 시연연상
https://getinthere.notion.site/932bc1ff75494b298d944bb6eed36ab5

### 4. 아키텍쳐
![image](https://user-images.githubusercontent.com/108394995/210051500-b1740556-2a00-4c7d-8314-69de845a5822.png)
- 스프링 기반의 개발에서 가장 보편적으로 사용되는 MVC 패턴을 이용함.
- Controller에 요청이 들어오면 Service에서 DAO 를 통해 DB와 통신 후 Controller로 Return 함. 이후 Controller는 Model에 담아 view에 데이터를 전달해줌


