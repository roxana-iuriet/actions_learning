FROM ubuntu:latest

ENV IN_PATH
ENV OUT_PATH

ADD script.sh /script.sh
RUN chmod +x /script.sh

ADD ${IN_PATH}

ENTRYPOINT ["/script.sh"]