# SEN-EVENT – Event Management Platform

**Domains:** Software

Web platform for publishing and managing events in Senegal.

## Features
- Create events with description, venue, date, schedule document, image, video and live-stream link.
- Categories, speakers, social links and ticket types with prices.
- Event registration with status tracking.
- Sign-up and login with email or Google, through django-allauth.
- User profiles and a public homepage listing events.
- Region and city reference data for Senegal.

## Stack
Python · Django · django-allauth with Google OAuth · SQLite · HTML templates

## Run locally
```bash
pip install django django-allauth pillow
python manage.py migrate
python manage.py runserver
```
`Sen-Event-Django_100` is an earlier version of this project, without Google login.
