FROM ubuntu:20.04
ADD ./ /souces 
RUN apt-get update -y && apt-get install python3-pip -y &&  pip3 install flask 
WORKDIR /souces 
ENV FLASK_APP=app.py
EXPOSE 8001
CMD flask run --host=0.0.0.0 --port=8001