FROM python:3.9

RUN pip install pandas

WORKDIR /app
COPY papeline.py papeline.py

ENTRYPOINT [ "python", "papeline.py" ]