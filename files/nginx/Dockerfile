FROM nginx:1.13
LABEL maintainer="sviplee@gmail.com"

# set timezone
ENV CNSH=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$CNSH /etc/localtime && echo $CNSH > /etc/timezone
