FROM python:3

WORKDIR /usr/src/app

RUN pip install --no-cache-dir nltk requests html2text

ADD src/parser.py /usr/src/app/

EXPOSE 8080
CMD /bin/bash
