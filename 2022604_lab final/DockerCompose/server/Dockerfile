FROM python:latest
WORKDIR /usr/src/app
COPY . .
RUN pip install flask
EXPOSE 5000
CMD [ "python", "server.py" ]