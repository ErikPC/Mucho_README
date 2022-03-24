FROM python:alpine

WORKDIR /home/app

COPY . .

RUN pip install pip-tools -q 
RUN pip-compile -q
RUN pip-sync -q

CMD ["python","-m","flask","run","-h","0.0.0.0"]