# PythonChainWallet

1. Clone the project 
`$ https://github.com/hoquandai/PythonChainWallet.git`
2. Install pip 
`$ sudo apt install python3-pip` or `$ sudo apt install python-pip`
2. Install virtualenv 
`$ pip3 install virtualenv` or `$ pip install virtualenv`
3. Create a virtual enviroment in your project directory 
`$ virtualenv venv`
4. Activate the virtual enviroment you created and run the following command:
`$ source venv/bin/activate`
5. Install the project requirements 
`$ pip install -r requirements.txt`
6. Migrate then run the project's backend server 
``` 
$ python manage.py migrate
$ python manage.py runserver 
```
7. Make sure that everything is working as expected by going to 127.0.0.1:8000/get_chain 
8. Run NodeJS server

9. **Done!**

*** CHÚ Ý
 - Source code tham khảo từ https://github.com/kemoszn/PyChain
 - Do không đủ thơì gian gia công nên còn dùng code Python, sẽ chuyển sang Code Ruby on Rails trong lần nộp tới ở bài tập nhóm
