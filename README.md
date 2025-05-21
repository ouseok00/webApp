# webApp

1. 새 폴더를 만들기
2. 만들 폴더에서 vs code를 들어가기
3. 터미널 ctrl + ~ 단축키를 눌러서 가상환경을 만들기
 ``` conda create -n webApp python=3.9 ```
  
![image](https://github.com/user-attachments/assets/c7de9852-e33d-40e7-af30-ffe0771d9d5a)

4. flask 프레임워크 설치
  ``` pip install flask ```

6. app.py 새 파일을 만들고 flask를 이용해서 app.py에 간단하게 이름, 전화번호를 입력 받아 addbook.txt에 csv로 저장하는 코드와 html를 만들기 위한 파일 생성
   app.py - flask를 이용해 이름과 전화번호를 입력받아 addbook.txt 파일에 csv 형식으로 저장하는 간단한 웹앱 코드
   
![image](https://github.com/user-attachments/assets/2bbd310d-11c7-4841-b358-bb1e6a569b67)

   templates/index.html - flask는 기본적으로 templates 폴더에서 html파일을 찾는다.
   
![image](https://github.com/user-attachments/assets/8858cd43-5c88-412a-a065-76cb6b2badfa)

8. 프로그램 실행
   ``` python app.py ```
   
브라우저에서 http://127.0.0.1:5000로 접속하여 이름과 전화번호를 입력하고 저장할 수 있다.

![image](https://github.com/user-attachments/assets/4db9cb19-4962-43b2-8c4d-68d8dedaf5f1)

9. addbook.txt에 저장된 모습
10. 
![image](https://github.com/user-attachments/assets/0f792852-a86e-41ba-adcc-39e19cf3b847)
