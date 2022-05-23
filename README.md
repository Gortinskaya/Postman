# Postman. HW_1
Создать запросы в Postman.

Protocol: http
IP: 162.55.220.72
Port: 5005

# EP_1
Method: GET
EndPoint: /get_method
request url params: 
 name: str
 age: int
 
Переименовать "New Request" в "EP1"
1. Выбрать метод GET, в поле "Enter request URL" дописать "/get_method"
2. выбрать "Params"
- в столбец "KEY" : "name" и "age"
- в столбец "VALUE" : "Mari" и "30" напротив ключей "name" и "age" соответственно
3. нажать Save и Send
response:

 
# EP_2
Method: POST
EndPoint: /user_info_3
request form data: 
 name: str
 age: int
 salary: int
 
# EP_3
Method: GET
EndPoint: /object_info_1
request url params: 
 name: str
 age: int
 weight: int
 
# EP_4
Method: GET
EndPoint: /object_info_2
request url params: 
 name: str
 age: int
 salary: int
 
# EP_5
Method: GET
EndPoint: /object_info_3
request url params: 
 name: str
 age: int
 salary: int
 
# EP_6
Method: GET
EndPoint: /object_info_4
request url params: 
 name: str
 age: int
 salary: int
 
# EP_7
Method: POST
EndPoint: /user_info_2
request form data: 
 name: str
 age: int
 salary: int
