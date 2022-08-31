FROM python:3
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
WORKDIR /aplicacao
COPY requirements.txt /aplicacao/
RUN pip install -r requirements.txt
COPY . /aplicacao/
#RUN python manage.py makemigrations
#RUN python manage.py migrate
