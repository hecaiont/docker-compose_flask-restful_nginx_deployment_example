FROM python:3.7

ADD . /www
WORKDIR /www

RUN python -m pip install --upgrade pip 
RUN pip3 install Flask
RUN pip install flask-restful
RUN pip3 install uwsgi

CMD uwsgi uwsgi.ini
