FROM python:3.9-buster

WORKDIR /opt/garmin-connector

COPY ./requirements.txt ./requirements.txt
RUN pip install -r ./requirements.txt

COPY gcexport-db.py gcexport-db.py

COPY ./garmin-connector ./garmin-connector

CMD [ "/opt/garmin-connector/garmin-connector" ]
