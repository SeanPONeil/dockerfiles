FROM debian:bullseye-slim
LABEL maintainer "Sean O'Neil <oneilse14@gmail.com>"

RUN apt-get update && apt-get install -y \
	cheese \
  mesa-utils \
  mesa-utils-extra \
  libxv1 \
  va-driver-all \
  systemd-sysv \
  dbus \
	--no-install-recommends \
	&& rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "cheese" ]
