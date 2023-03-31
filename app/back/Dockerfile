FROM python:3.6
EXPOSE 3000
WORKDIR /app
COPY requirements.txt .
COPY back.py .
RUN pip install -r requirements.txt
CMD ["python","back.py"]
