FROM python:3
EXPOSE 80
WORKDIR /usr/src/app
COPY . /usr/src/app/
RUN pip3 install -r requirements.txt
CMD ["flask", "run", "--host=0.0.0.0", "--port=80"]