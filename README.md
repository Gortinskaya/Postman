# <p><a href="#P">Postman. HW_1</a></p>
<p><a href="#1">EP_1/get_method</a></p>
<p><a href="#2">EP_2/user_info_3</a></p>
<p><a href="#3">EP_3/object_info_1</a></p>
<p><a href="#4">EP_4/object_info_2</a></p>
<p><a href="#5">EP_5/object_info_3</a></p>
<p><a href="#6">EP_6/object_info_4</a></p>
<p><a href="#7">EP_7/user_info_2</a></p>

___________________________
 # <p><a name="P">Postman. HW_1</a></p>

### Создать запросы в Postman.

Protocol: http

IP: 162.55.220.72

Port: 5005
________
# <p><a name="1">EP_1</a></p>
Method: GET

EndPoint: /get_method

request url params:

 1. name: str
 2. age: int
 
 **Создать "New Request", переименовать в "EP_1"**
1. Выбрать метод GET, в поле "Enter request URL" после порта дописать "/get_method"
2. выбрать "Params"
- в столбец "KEY" : "name" и "age"
- в столбец "VALUE" : "Mari" и "30" напротив ключей "name" и "age" соответственно
3. нажать Save и Send

response:
[
    "Mari",
    "30"
]

 _____________________
# <p><a name="2">EP_2</a></p>
Method: POST

EndPoint: /user_info_3

request form data: 

 1. name: str
 2. age: int
 3. salary: int

**Создать "New Request", переименовать в "EP_2"**
1. Выбрать метод POST, в поле "Enter request URL" после порта дописать "/user_info_3"
2. выбрать "body"
- в столбец "KEY" : "name", "age" и "salary"
- в столбец "VALUE" : "Mari", "30" и "2000" напротив ключей "name", "age" и "salary" соответственно
3. нажать Save и Send

response:
{
    "age": "30",
    "family": {
        "children": [
            [
                "Alex",
                24
            ],
            [
                "Kate",
                12
            ]
        ],
        "u_salary_1_5_year": 8000
    },
    "name": "Mari",
    "salary": 2000
}

 _________________________
# <p><a name="3">EP_3</a></p>
Method: GET

EndPoint: /object_info_1

request url params: 
 1. name: str
 2. age: int
 3. weight: int

 **Создать "New Request", переименовать в "EP_3"**
1. Выбрать метод GET, в поле "Enter request URL" после порта дописать "/object_info_1"
2. выбрать "Params"
- в столбец "KEY" : "name", "age" и "weight"
- в столбец "VALUE" : "Mari", "30" и "60" напротив ключей "name", "age" и "weight" соответственно
3. нажать Save и Send

response:
{
    "age": 30,
    "daily_food": 0.78,
    "daily_sleep": 162.5,
    "name": "Mari"
}

 _____________________________
# <p><a name="4">EP_4</a></p>
Method: GET

EndPoint: /object_info_2

request url params: 
 1. name: str
 2. age: int
 3. salary: int

**Создать "New Request", переименовать в "EP_4"**
1. Выбрать метод GET, в поле "Enter request URL" после порта дописать "/object_info_2"
2. выбрать "Params"
- в столбец "KEY" : "name", "age" и "salary"
- в столбец "VALUE" : "Mari", "30" и "2000" напротив ключей "name", "age" и "salary" соответственно
3. нажать Save и Send

response:
{
    "person": {
        "u_age": 30,
        "u_name": [
            "Mari",
            2000,
            30
        ],
        "u_salary_5_years": 8400.0
    },
    "qa_salary_after_1.5_year": 6600.0,
    "qa_salary_after_12_months": 5400.0,
    "qa_salary_after_3.5_years": 7600.0,
    "qa_salary_after_6_months": 4000,
    "start_qa_salary": 2000
}

 ________________________________
# <p><a name="5">EP_5</a></p>
Method: GET

EndPoint: /object_info_3

request url params: 
 1. name: str
 2. age: int
 3. salary: int

 **Создать "New Request", переименовать в "EP_5"**
1. Выбрать метод GET, в поле "Enter request URL" после порта дописать "/object_info_3"
2. выбрать "Params"
- в столбец "KEY" : "name", "age" и "salary"
- в столбец "VALUE" : "Mari", "30" и "2000" напротив ключей "name", "age" и "salary" соответственно
3. нажать Save и Send

response:
{
    "age": "30",
    "family": {
        "children": [
            [
                "Alex",
                24
            ],
            [
                "Kate",
                12
            ]
        ],
        "pets": {
            "cat": {
                "age": 3,
                "name": "Sunny"
            },
            "dog": {
                "age": 4,
                "name": "Luky"
            }
        },
        "u_salary_1_5_year": 8000
    },
    "name": "Mari",
    "salary": 2000
}

 ____________________________________ 
 # <p><a name="6">EP_6</a></p>
Method: GET

EndPoint: /object_info_4

request url params: 
 1. name: str
 2. age: int
 3. salary: int

**Создать "New Request", переименовать в "EP_6"**
1. Выбрать метод GET, в поле "Enter request URL" после порта дописать "/object_info_4"
2. выбрать "Params"
- в столбец "KEY" : "name", "age" и "salary"
- в столбец "VALUE" : "Mari", "30" и "2000" напротив ключей "name", "age" и "salary" соответственно
3. нажать Save и Send 

response:
{
    "age": 30,
    "name": "Mari",
    "salary": [
        2000,
        "4000",
        "6000"
    ]
}
 ________________________________________
# <p><a name="7">EP_7</a></p>
Method: POST

EndPoint: /user_info_2

request form data: 
 1. name: str
 2. age: int
 3. salary: int

**Создать "New Request", переименовать в "EP_4"**
1. Выбрать метод POST, в поле "Enter request URL" после порта дописать "/user_info_2"
2. выбрать "Body"
- в столбец "KEY" : "name", "age" и "salary"
- в столбец "VALUE" : "Mari", "30" и "2000" напротив ключей "name", "age" и "salary" соответственно
3. нажать Save и Send

response:
{
    "person": {
        "u_age": 30,
        "u_name": [
            "Mari",
            2000,
            30
        ],
        "u_salary_5_years": 8400.0
    },
    "qa_salary_after_1.5_year": 6600.0,
    "qa_salary_after_12_months": 5400.0,
    "qa_salary_after_3.5_years": 7600.0,
    "qa_salary_after_6_months": 4000,
    "start_qa_salary": 2000
}
