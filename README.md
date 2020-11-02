# Minimalis Flask Blog
The Simple Blog App Built with Flask

## Features
- Sign Up Account
- Login Account
- Logout Account
- Add Post
- Update Post
- Delete Post

## Installation on Heroku
- Install on Python 3.7+
- Do git add, commit, push to Heroku

     `$ git push heroku master`
     
- Create db in Heroku
    ```
    $ heroku run python
    $ from blog import db
    $ db.create_all()
    ```
- Set SECRET_KEY in Heroku account, menu: Config Vars

## Live Demo on Heroku

http://minimalisflaskblog.herokuapp.com/