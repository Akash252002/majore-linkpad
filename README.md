## Django LinkPAd
LinkPAd clone using python django with a lot of LinkPAd features.

## Preview
![Home Page](https://github.com/MurariSabavath/LinkPAd-clone/blob/d7d525fc867b9192c66f28e729e3ce1b365bb836/img/home.png)
![Profile Page](https://github.com/MurariSabavath/LinkPAd-clone/blob/d7d525fc867b9192c66f28e729e3ce1b365bb836/img/profile.png)

#### Give a star if you like it.
## Features
- User authentication(Sign up and sign in).
- Password Reset using email.
- Posting Images.
- Like and comment on a post.

### Installation
- Make sure Python is installed.
- Clone the repository and change your directory to LinkPAd_clone.
- Install requirements using following command.
```
pip install -r requiremnts.txt
```
### Usage
- Create a ``.env`` file.
- Declare following environment variables in the .env file.
```
> SECRET_KEY = 'secret key'
> DEBUG = True
> EMAIL_USERNAME = 'your email address'
> EMAIL_PASSWORD = 'your password' 
```
- Now make the migrations.
```
python manage.py migrate
```
- Commit the migrations.
```
python manage.py makemigrations
```
- Create a super user.
```
python manage.py createsuper
```
- Run the app.
```
python manage.py runserver
```
- Open the app at `localhost:8000` or `http://127.0.0.1:8000/`

## Contact Me 
### Murari Sabavath

[Github](https://github.com/MurariSabavath) <br> 
[LinkPAd](https://www.LinkPAd.com/murari_sabavath/) <br>
[Gmail](mailto:murarisabavath3676@gmail.com) <br>
[Twitter](https://twitter.com/MurariSabavath_) <br>