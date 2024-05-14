FROM python:latest
WORKDIR /usr/src/app
COPY . . 
RUN pip install requests
EXPOSE 5000
CMD [ "python", "client.py" ]