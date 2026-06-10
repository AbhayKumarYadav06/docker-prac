FROM python:slim

WORKDIR /pandas-demo

COPY requirements.txt .
RUN pip install -r requirements.txt
COPY demo_pandas.py .

CMD ["python", "demo_pandas.py"]