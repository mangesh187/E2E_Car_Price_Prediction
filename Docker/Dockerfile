FROM python:3.8

COPY requirements.txt .


RUN pip install -r requirements.txt


COPY . .

CMD ["uwsgi","--ini","app.ini"]

EXPOSE 5000