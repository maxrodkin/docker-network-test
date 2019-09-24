FROM ubuntu
RUN apt-get update && apt-get install -y iputils-ping
RUN apt-get install traceroute
#CMD ["/bin/ping","-c","4","8.8.8.8"]
CMD ["/usr/sbin/traceroute","8.8.8.8"]
