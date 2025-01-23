FROM python:3.6
WORKDIR /app
COPY . .
RUN pip install fastapi
RUN pip install uvicorn
RUN pip install passlib
RUN pip install jinja2
RUN pip install python-multipart
CMD ["uvicorn", "main.py", "--host", "0.0.0.0", "--port", "8000"]
