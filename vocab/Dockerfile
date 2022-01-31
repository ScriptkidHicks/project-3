FROM python:3.8
LABEL maintainer="tammas@webmail.uoregon.edu"
MAINTAINER Tammas Hicks
RUN apt-get update -y
COPY . /app
WORKDIR /app
RUN python -m pip install -U pip
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["flask_vocab.py"]
