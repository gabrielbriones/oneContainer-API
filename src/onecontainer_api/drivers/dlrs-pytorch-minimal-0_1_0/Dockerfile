FROM python:slim

WORKDIR /workspace

RUN pip install pip --upgrade
COPY requirements.txt .
RUN pip install -U  -r requirements.txt
COPY . .

#ENTRYPOINT [ "python", "./client.py" ]
