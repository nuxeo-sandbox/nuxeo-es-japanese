FROM nuxeo:9.10

USER root

RUN mkdir -p /opt/nuxeo/server/packages/store
RUN chown -R 1000:1000 /opt/nuxeo/server/packages

RUN apt-get update && apt-get install fonts-takao mediainfo vim iproute2 ffmpeg x264 -y --no-install-recommends

USER 1000
