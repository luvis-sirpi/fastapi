FROM python:3.6
COPY app /app
WORKDIR /app
RUN pip install fastapi
RUN pip install uvicorn
RUN pip install passlib
RUN pip install jinja2
RUN pip install python-multipart
EXPOSE 8000
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000"]
