FROM python:3
ADD ./web /usr/src/app
WORKDIR /usr/src/app
RUN pip install -r requirements.txt
CMD ["python", "app.py"]
