#Build it
#docker build -t ex00
#
#run
#docker run --rm -ti ex00


FROM alpine

RUN apk update &&\
	apk upgrade &&\
	apk add vim

ENTRYPOINT vim
