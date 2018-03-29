FROM python:2.7
MAINTAINER Aashish Chetwani "aashish.chetwani@opcito.com"
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["app.py"]

