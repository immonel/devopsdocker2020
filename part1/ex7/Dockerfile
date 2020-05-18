FROM ubuntu:16.04
WORKDIR /
COPY curler.sh .
RUN apt-get update
RUN apt-get install curl -y
RUN chmod +x curler.sh
CMD ["/bin/bash", "./curler.sh"]
