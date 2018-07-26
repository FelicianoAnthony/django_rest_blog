# Django REST API -- Create Read Update Delete 

`activate/deactivate env` 


`python manage.py runserver `




### log in to admin -- http://localhost:8000/admin/

![alt text](screenshots/admin.png)


### posts home -- http://localhost:8000/admin/posts/post/

![alt text](screenshots/posts_home.png)


### to make a POST -- http://localhost:8000/admin/posts/

![alt text](screenshots/make_post.png)


### to view all POSTS -- http://127.0.0.1:8000/api/ 

![alt text](screenshots/list_posts.png)


### to view a specific post based on ID  -- http://127.0.0.1:8000/api/4/ 

![alt text](screenshots/put_delete.png)

`
activating venv on windows...

1. c:/Python27/python.exe   c:/virtualenv/virtualenv.py   c:/projects/new_env
2. cd new_env -- must be in Scripts directory 
3. activate
4. pip install django 

to find python path - 
import os,sys
os.path.dirname(sys.executable)

to find virtualenv path (once installed)
pip show virtualenv

https://wsvincent.com/django-rest-framework-tutorial/
http://www.pfinn.net/install-pip-virtualenv-on-windows.html 


`
