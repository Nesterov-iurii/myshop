# myshop

This is a simple e-commerce application which has:

Shopping cart supporting anonymous users
Asynchronous tasks with Python Celery
RabbitMQ to improve component decoupling
Payment gateway with Braintree
Using WeasyPrint to auto-generate pdf files of user orders
Coupon system
I18n and L10n (Russian, unfinished)

HOW TO RUN THIS APP:

Download the repository in the command line:
pip install requirements.txt
get API credentials from https://www.braintreepayments.com/sandbox
run Message queue - I use RabbitMQ for this project
python manage.py runserver
Open the IP address which django server provides to you
