# No Dockerhub standard flask containers exist as of 2020-09-14 - NWW
FROM python:3.7-alpine
RUN pip install Flask

WORKDIR /app

ADD app.py /app
ENV FLASK_APP app.py

CMD ["flask", "run"]