# url shortener project
shortens the given url:

1.run shortener app<br>
2.put link in target url post<br>
3.get user shorter name from response<br>

welcome page: http://127.0.0.1:8000
work page: http://127.0.0.1:8000/docs

Install the Project
Create a Python virtual environment
$ python -m venv venv
$ source venv/bin/activate
(venv) $
Install the requirements
(venv) $ python -m pip install -r requirements.txt
Run the Project
You can run the project with this command in your terminal:

(venv) $ uvicorn shortener_app.main:app --reload
Your server will reload automacially when you change a file.

enter here: http://127.0.0.1:8000/docs and start to use
