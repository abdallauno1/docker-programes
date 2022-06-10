FROM alpine:latest
LABEL maintainer "Abdalla Mady <abdullamady@hotmail.com>"
RUN apk --no-cache add \
	ca-certificates \
	python \
	py2-pip \
	&& pip install cli53

ENTRYPOINT [ "cli53" ]
