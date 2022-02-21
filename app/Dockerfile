FROM python:3.9-slim-bullseye
WORKDIR /app
COPY ./requirements.txt /app/requirements.txt
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
COPY . /app
RUN pip3 install -r requirements.txt
CMD ["python3", "app.py"]