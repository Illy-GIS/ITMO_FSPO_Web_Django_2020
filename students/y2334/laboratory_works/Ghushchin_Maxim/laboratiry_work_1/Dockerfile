FROM python:3.8-alpine
WORKDIR /app
COPY restaurant .
RUN pip install -r requirements.txt
CMD ["python3", "manage.py", "runserver", "0.0.0.0:8000"]