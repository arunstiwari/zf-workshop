ARG IMAGE_VERSION=20.04
FROM ubuntu:$IMAGE_VERSION
ARG USER=TestUser
LABEL maintainer=arunstiwari@gmail.com
LABEL version=1.0
LABEL evironment=dev

RUN apt-get update
RUN apt install nginx -y

WORKDIR one

ENV VERSION 1.0
ENV PATH $PATH:/usr/local/myapp/bin

# ENTRYPOINT ["echo", "Hello"]
# CMD ["env"]
CMD ["pwd"]
