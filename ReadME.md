# Project Scrapmart
## Deployed Version of the Project
https://scrapmart.onrender.com/

## Note 

Scrapmart uses PostgresSQL as backend, so make sure you have it installed and change the databases section in settings.py before running the app.


## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/rishabhjain1712/scrapmart.git
$ cd scrapmart
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ virtualenv2 --no-site-packages env
$ source env/bin/activate
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv2`.

Once `pip` has finished downloading the dependencies:
```sh
(env)$ python manage.py runserver
```
And navigate to `http://127.0.0.1:8000/`.


Screenshots:

![1](https://user-images.githubusercontent.com/72996825/124763728-ead36680-df51-11eb-8842-66a1e1b1ee81.PNG)
![2](https://user-images.githubusercontent.com/72996825/124763741-ec9d2a00-df51-11eb-86e6-ce31ab9bf710.PNG)
![5](https://user-images.githubusercontent.com/72996825/124763747-edce5700-df51-11eb-9386-282ddbd0a86d.PNG)
![6](https://user-images.githubusercontent.com/72996825/124763748-edce5700-df51-11eb-817b-e00ab59dd7d8.PNG)
![7](https://user-images.githubusercontent.com/72996825/124763750-ee66ed80-df51-11eb-832b-11a1a62d0a34.PNG)
![9](https://user-images.githubusercontent.com/72996825/124763755-eeff8400-df51-11eb-9eb9-438da4f14538.PNG)
![10](https://user-images.githubusercontent.com/72996825/124763757-ef981a80-df51-11eb-85d2-033cb402c65e.PNG)



