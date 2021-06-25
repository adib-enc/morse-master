FROM python:3.7
WORKDIR /app
COPY . .
RUN pip3 install -r requirements.txt

CMD ["uvicorn","main:app","--reload","--host","0.0.0.0"]
EXPOSE 8000