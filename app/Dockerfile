FROM python:3.10-slim

WORKDIR /app
COPY . .
RUN pip install flask redis pytest

CMD ["python", "app.py"]