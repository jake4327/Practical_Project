FROM python:3.7
WORKDIR ./backend
COPY . . 
RUN pip install -r requirements.txt
EXPOSE 5001
ENTRYPOINT ["python", "app.py"]
