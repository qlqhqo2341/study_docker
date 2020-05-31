FROM debian:latest

# RUN perl -pi -e 's/deb.debian.org/ftp.kr.debian.org/g' /etc/apt/sources.list
    # perl -pi -e 's/security.debian.org/ftp.kr.debian.org/g' /etc/apt/sources.list

RUN apt-get update && apt-get install -y \
 vim-tiny wget python python3 python3-pip build-essential\
 && rm -rf /var/lib/apt/*