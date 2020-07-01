FROM gobuffalo/buffalo:v0.16.10

COPY ./app /src/app

WORKDIR /src/app

RUN buffalo build --static -o /bin/app

ENV ADDR=0.0.0.0

CMD [ "/bin/app" ]