FROM python:3.6
WORKDIR /app
COPY . .
RUN pip install fastapi
RUN pip install uvicorn
RUN pip install passlib
RUN pip install jinja2
RUN pip install python-multipart
EXPOSE 8000
CMD ["python","main.py"]
