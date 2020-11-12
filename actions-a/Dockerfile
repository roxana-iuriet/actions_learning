FROM ubuntu:latest

ARG IN_PATH
ARG OUT_PATH

ADD script.sh /script.sh
RUN chmod +x /script.sh

ADD ${IN_PATH} /

ENTRYPOINT ["/script.sh"]