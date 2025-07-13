# ALX Travel App 0x03

This project demonstrates background task handling in Django using **Celery with RabbitMQ**, and sending **asynchronous booking confirmation emails**.

## Features

- 🎯 Booking creation triggers background email via Celery
- 📨 Emails are sent using Django email backend
- 🐇 RabbitMQ as Celery broker
- 🧵 Fully decoupled async tasks

## Run Celery

```bash
celery -A alx_travel_app worker --loglevel=info
