FROM	ruby:alpine
LABEL maintainer "Abdalla Mady <abdullamady@hotmail.com>"

RUN	apk add --no-cache \
	libcurl

RUN	set -x \
	&& apk add --no-cache --virtual .build-deps \
	build-base \
	&& gem install cloudapp --no-document \
	&& apk del .build-deps

ENTRYPOINT	["cloudapp"]
