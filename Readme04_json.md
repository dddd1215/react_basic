
![image](https://github.com/dddd1215/react_basic/assets/129017020/11e5acd0-586d-46a2-bc22-4a20a5c04534)
npm i json-server

# db.json 파일 만들기
![image](https://github.com/dddd1215/react_basic/assets/129017020/63cf67ca-2baa-4614-96b1-c79203606ea7)
# db.jsonvkdlfdms root에 만들어야한다.
![image](https://github.com/dddd1215/react_basic/assets/129017020/d5a9584e-69ba-417e-9e52-24bee3b5b091)

![image](https://github.com/dddd1215/react_basic/assets/129017020/4c23e323-cff3-4d75-a553-2fc6382c7db3)
# 위와 같이 실행하면 port를 3000번 사용하기 때문에 react와 중복이 되어버린다.
# 그래서 port를 변경해주어야 한다.
json-server --watch db.json --port 3004
# 혹 실행이 안된다면 아래를 적용한다.
  npx json-server --watch db.json --port 3004

# 서버와 통신하기
![image](https://github.com/dddd1215/react_basic/assets/129017020/b1d6fd85-5f42-4310-92a3-606043991d9e)

    npm i axios

![image](https://github.com/dddd1215/react_basic/assets/129017020/c256397c-3cad-42d6-b45f-67d8ef116207)
