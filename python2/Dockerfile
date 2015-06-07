FROM python:2.7.10
COPY requirements.txt /src/
RUN cd /src && pip install -r requirements.txt
WORKDIR /src
ENTRYPOINT ["python"]
