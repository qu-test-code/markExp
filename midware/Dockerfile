FROM python:3

RUN mkdir /midware

COPY requirements.txt /midware/
COPY start.sh /midware/

WORKDIR /midware

RUN pip install -r /midware/requirements.txt

COPY expapp.py /midware/

CMD ./start.sh