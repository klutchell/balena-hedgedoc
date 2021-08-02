FROM ghcr.io/linuxserver/hedgedoc:1.8.2-ls24

COPY 97-hostname /etc/cont-init.d/

RUN chmod 0755 /etc/cont-init.d/97-hostname

ENV DEVICE_HOSTNAME hedgedoc
