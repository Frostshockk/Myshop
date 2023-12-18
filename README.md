# Myshop
Course Project PKSP. Made by Kirill Gorokhov BFI2001. Python 3.8 + Django 4.7.0
# What is this ?
This is a shop that includes:
1) Cart system
2) Payment system
3) Coupon system
4) Emal massages about order
5) Translation ru/eng
#How to run ?
1) Download the project
2) Start rabbitMQ service
3) Open the therminal
4) python manage.py runserver
5) celery -A myshop flower
6) celery -A myshop worker -l info (emain example in therminal)
