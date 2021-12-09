# village-market

Django (Backend)
--------------------
$ pip install djangorestframework
$ pip install markdown       
$ pip install django-filter

$ python -m venv env
$ env\Scripts\activate

$ pip3 freeze > requirements.txt  # Python3
$ pip freeze > requirements.txt  # Python2

$ COPY requirements.txt /app/requirements.txt  
$ RUN pip install -r /app/requirements.txt

Vue.Js Installation:(Frontend)
---------------------------------
# latest stable
$ npm install vue@next

# OR
npm install -g @vue/cli

#Project Create
# npm 6.x
$ npm init vite@latest campus-vive-frontend --template vue

# npm 7+, extra double-dash is needed:
$ npm init vite@latest <project-name> -- --template vue

>>>Or Else>>> $ vue create project-name 

$ cd <project-name>
$ npm install
$ npm run dev

Resources:
https://www.telerik.com/blogs/10-good-practices-building-maintaining-large-vuejs-projects
https://dev.to/champi/front-end-best-practices-featuring-vuejs-1b5p