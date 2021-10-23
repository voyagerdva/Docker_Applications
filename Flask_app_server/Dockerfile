FROM python:3.9

RUN mkdir -p /opt/app
WORKDIR /opt/app

COPY . /opt/app
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8080

CMD ["python", "app.py"]
