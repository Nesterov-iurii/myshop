# myshop

This is a simple e-commerce application which has:

1. Shopping cart supporting anonymous users
2. Asynchronous tasks with Python Celery
3. RabbitMQ to improve component decoupling
4. Payment gateway with Braintree
5. Using WeasyPrint to auto-generate pdf files of user orders
6. Coupon system
7. I18n and L10n (Russian, unfinished)

HOW TO RUN THIS APP:

1. Download the repository in the command line:
2. pip install requirements.txt
3. get API credentials from https://www.braintreepayments.com/sandbox
4. run Message queue - I use RabbitMQ for this project
5. python manage.py runserver
6. Open the IP address which django server provides to you
