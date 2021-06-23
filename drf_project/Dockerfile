FROM python:3.8.3

WORKDIR /drf_project

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY /drf_project .

CMD ["python", "manage.py", "runserver"]