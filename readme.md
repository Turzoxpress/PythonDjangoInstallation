# How to create a Python Django project?
Make sure you have python 3 installed on your machine. This tutorial will be covered based on Ubuntu 20 OS. <br>

[Visit this link if you didn't install Python yet!](https://www.python.org/downloads/) 

* Check your Python installed successfully or not <br>

```python 
  python3 --version
```
* Update the packages <br>

```python 
  sudo apt update
```

* Install **pip** and **Python Virtual Environment**  <br>

```python 
  sudo apt install python3-pip python3-venv
```

* Create a new directory in  your machine and allow **Read Write** permission to it  <br>

```python 
  sudo mkdir test
  cd test
  sudo chmod -R 777 ./ #You can edit permission later
```


* Create your **Python Virtual Environment**, here I named it **my_env**  <br>

```python 
  python3 -m venv my_env
```

* Enable your virtual environment  <br>

```python 
  source my_env/bin/activate
```

* Install **Django**  <br>

```python 
  pip install django
```

* Check Django installed successfully or not  <br>

```python 
  django-admin --version
```

* Create a new project with Django   <br>

```python 
  
  django-admin startproject my_project 

  cd my_project 

  ls # You will see a file named manage.py
  
```

* Now, **Start the server!** <br>

```python 
  python3 manage.py runserver
```

A server will run on your machine on 8000 port. <br>
Now open your browser and copy and paste the link **http://127.0.0.1:8000/** or **http://localhost:8000** or **localhost:8000**

### If you see something like the screenshot below then **Congratulation!** You successfully installed **Python Django** on your machine. <br><br>

![Alt text](/screenshots/_django_installation.JPG "Python Django")

