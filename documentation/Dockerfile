FROM squidfunk/mkdocs-material

WORKDIR /docs

COPY requirements.txt requirements.txt

RUN pip install -r requirements.txt


EXPOSE 8000

CMD [ "serve", "-a", "0.0.0.0:8000" ]
