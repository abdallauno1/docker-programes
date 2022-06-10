FROM debian:sid-slim
LABEL maintainer "Abdalla Mady <abdullamady@hotmail.com>"

RUN apt-get update && apt-get install -y \
	apt-file \
	--no-install-recommends \
	&& rm -rf /var/lib/apt/lists/*

CMD [ "bash" ]
