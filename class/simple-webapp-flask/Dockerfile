FROM ubuntu

RUN apt-get update
RUN apt-get install -y python python-pip git
RUN pip install flask
RUN git clone https://github.com/mmumshad/simple-webapp-flask.git

ENTRYPOINT FLASK_APP=/simple-webapp-flask/app.py flask run --host=0.0.0.0
