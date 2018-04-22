FROM scratch
ADD alpine-minirootfs-3.7.0-armhf.tar.gz /
RUN echo "http://mirrors.aliyun.com/alpine/v3.7/main" >/etc/apk/repositories \
        && echo "http://mirrors.aliyun.com/alpine/v3.7/community" >>/etc/apk/repositories \
        && echo "http://mirrors.aliyun.com/alpine/v3.7/testing" >>/etc/apk/repositories
