FROM ubuntu:latest

RUN apt-get update && apt-get install -y curl

#RUN yum install -y curl

ADD script.sh /script.sh
RUN chmod +x /script.sh

ENTRYPOINT ["/script.sh"]