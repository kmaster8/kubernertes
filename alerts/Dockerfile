FROM python:3.8-slim
MAINTAINER kmaster <kmaster8k@gmail.com>

COPY . /app
WORKDIR /app

RUN pip3 install flask 

EXPOSE 5000
CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0"]
