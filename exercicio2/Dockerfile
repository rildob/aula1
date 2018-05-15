FROM python:alpine
COPY . /usr/src/
WORKDIR /usr/src
RUN pip install -r requirements.txt
ENV FLASK_APP=app.py
CMD ["flask","run","--host","0.0.0.0"]
