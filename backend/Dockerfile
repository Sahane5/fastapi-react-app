FROM python:3.10-slim

WORKDIR /app

COPY requirements.txt /app/
RUN pip install -r requirements.txt

EXPOSE 8000

CMD ["uvicorn main:app --reload", "--host" "0.0.0.0"]

