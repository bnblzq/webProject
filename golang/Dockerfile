FROM golang:latest
LABEL maintainer="sijianliu"




WORKDIR /code
COPY ./sproxy /code
RUN chmod a+x ./sproxy
EXPOSE 8080
CMD ["tail -F anything"]
