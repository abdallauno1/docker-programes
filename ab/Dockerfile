# ab (apache benchmark)
# in a container
#
# docker run --rm -it \
# 	
#
FROM alpine:latest
LABEL maintainer "Abdalla Mady <abdullamady@hotmail.com>"

RUN apk --no-cache add \
	apache2-ssl \
	apache2-utils \
	ca-certificates \
	htop

ENTRYPOINT [ "ab" ]
