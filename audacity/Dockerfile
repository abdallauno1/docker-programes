FROM debian:sid-slim
LABEL maintainer "Abdalla Mady <abdullamady@hotmail.com>"

RUN apt-get update && apt-get install -y \
	audacity \
	--no-install-recommends \
	&& rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "audacity" ]
