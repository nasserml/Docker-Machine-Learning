FROM ubuntu:18.04
COPY . /app
WORKDIR /app
RUN apt-get update -y
Run apt-get install -y python-pip python-dev build-essential
RUN pip install -r requirements.txt
EXPOSE 5000
CMD python ./index.py