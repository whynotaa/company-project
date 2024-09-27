프로젝트 협업
1. 코드 복사
![image](https://github.com/user-attachments/assets/8f068c24-162e-4c6e-b40b-71134f28f78e)

2. 터미널 열기
   
   git clone "복사한코드" "설정할 폴더 이름"

   ##이 레포지토리로부터 복사할건데 어떤 폴더 이름으로 넣고 싶니 
   
   ![image](https://github.com/user-attachments/assets/29faeb6d-97ba-4208-b333-0210555975d8)

4. 설정한 폴더이름으로 들어가기
   
   cd "설정한 폴더 이름"
   
   code .
   
-> vscode가 열릴것임
   
5. 프로젝트 수행한것 올리기
   vs code 터미널에서 
   
   git add . #깃에 저장
   
   git commit -m "~~" # 나의 히스토리 남기기

   ((git push origin master ( 절대 해서는 안됨 )# 마스터라는 최종 브랜치에 넣겠다는 의미
   
   -> 나를 위한 공간에 넣어줌))
   
   git checkout -b 공간이름 #잔가지 마스터가 아닌 신입이 작업하는 공간을 따로 만들어줌
   
-> 신입이 작업하는 공간으로 들어오게 됨
   
   git push origin "공간이름"

4-1. 마스터의 코드 동기화 

   마스터가 수정한 코드 날라가지않게 저장 
   
   git add .
   
   git commit -m "~~commit"
      
   git pull origin master  # 바뀐 내용 덮어쓰기 
   

   -> 마스터 브랜치로부터 동기화됨 

   
   


   
   
   
