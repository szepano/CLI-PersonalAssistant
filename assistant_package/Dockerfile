FROM python:3.11

ENV APP_HOME /app

WORKDIR ${APP_HOME}

COPY ./assistant /app/assistant
COPY requirements.txt .

RUN pip install -r requirements.txt
RUN pip install ./assistant

EXPOSE 5000

