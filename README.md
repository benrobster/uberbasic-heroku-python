UBER BASIC HEROKU PYTHON APP
============================

1) Install Heroku toolbelt if you haven't already (you'll need to create an account as well)

2) Clone repository into a directory (git clone https://github.com/nebstrebor/uberbasic-heroku-python.git )

3) cd uberbasic-heroku-python

4) create app: heroku create

5) deploy: run git push heroku master

6) turn it on: heroku ps:scale app=1 

7) See it working: run heroku logs --tail