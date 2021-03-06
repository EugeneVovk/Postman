# Postman
Postman. HW_1  

Создать запросы в Postman.

Protocol: http
IP: 162.55.220.72
Port: 5005

![Image alt](https://github.com/EugeneVovk/Postman/raw/main/img/EP_1.png)

EP_1
Method: GET
EndPoint: /get_method
request url params: 
 name: str
 age: int

response: 
[
    “Str”,
    “Str”
]

![Image alt](https://github.com/EugeneVovk/Postman/raw/main/img/EP_1.get_method.png)

==================

EP_2
Method: POST
EndPoint: /user_info_3
request form data: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'u_salary_1_5_year': salary * 4}}

![Image alt](https://github.com/EugeneVovk/Postman/raw/main/img/EP_2.user_info_3.png)

==================

EP_3
Method: GET
EndPoint: /object_info_1
request url params: 
 name: str
 age: int
 weight: int

response: 
{'name': name,
          'age': age,
          'daily_food': weight * 0.012,
          'daily_sleep': weight * 2.5}

![Image alt](https://github.com/EugeneVovk/Postman/raw/main/img/EP_3.object_info_1.png)

==================

EP_4
Method: GET
EndPoint: /object_info_2
request url params: 
 name: str
 age: int
 salary: int

response: 
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }

![Image alt](https://github.com/EugeneVovk/Postman/raw/main/img/EP_4.object_info_2.png)

==================

EP_5
Method: GET
EndPoint: /object_info_3
request url params: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'pets': {'cat':{'name':'Sunny',
                                     'age': 3},
                              'dog':{'name':'Luky',
                                     'age': 4}},
                     'u_salary_1_5_year': salary * 4}
          }

![Image alt](https://github.com/EugeneVovk/Postman/raw/main/img/EP_5.object_info_3.png)

==================

EP_6
Method: GET
EndPoint: /object_info_4
request url params: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': int(age),
          'salary': [salary, str(salary * 2), str(salary * 3)]}

![Image alt](https://github.com/EugeneVovk/Postman/raw/main/img/EP_6.object_info_4.png)

==================

EP_7
Method: POST
EndPoint: /user_info_2
request form data: 
 name: str
 age: int
 salary: int

response: 
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }
		  
![Image alt](https://github.com/EugeneVovk/Postman/raw/main/img/EP_7.user_info_2.png)


Прогон:

![Image alt](https://github.com/EugeneVovk/Postman/raw/main/img/HW_1.run.png)		  
