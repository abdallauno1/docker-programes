FROM debian:sid-slim
LABEL maintainer "Abdalla Mady <abdullamady@hotmail.com>"

RUN apt-get update && apt-get install -y \
	adb \
	android-tools* \
	ca-certificates \
	curl \
	fastboot \
	usbutils \
	--no-install-recommends \
	&& rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "bash" ]
