FROM ubuntu:22.04

RUN apt update && \
    apt install -y telnet net-tools iputils-ping && \
    useradd -m roboshop

USER roboshop

CMD ["sleep","100000"]