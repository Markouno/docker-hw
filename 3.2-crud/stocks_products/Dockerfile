FROM python:3.11

WORKDIR /usr/src/django-project

COPY ./requirements.txt /usr/src/django-project/requirements.txt
RUN pip install -r /usr/src/django-project/requirements.txt

COPY . /usr/src/django-project/

EXPOSE 8000

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]