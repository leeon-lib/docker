FROM mysql:5.7
LABEL maintainer="sviplee@gmail.com"

# set timezone
ENV CNSH=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$CNSH /etc/localtime && echo $CNSH > /etc/timezone
