FROM debian:latest

RUN perl -pi -e 's/deb.debian.org/ftp.kaist.ac.kr/g' /etc/apt/sources.list && \
    perl -pi -e 's/security.debian.org/ftp.kaist.ac.kr/g' /etc/apt/sources.list

RUN apt-get update && apt-get install -y \
 vim-tiny \
 && rm -rf /var/lib/apt/*