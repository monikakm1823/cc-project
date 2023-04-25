FROM python

RUN apt-get update

RUN pip install flask

RUN pip install pymongo

COPY app.py app.py

CMD ["python", "app.py"]