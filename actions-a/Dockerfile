FROM ubuntu:latest

RUN yum install y curl

ADD script.sh /script.sh
RUN chmod +x /script.sh

ENTRYPOINT ["/script.sh"]