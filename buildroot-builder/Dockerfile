FROM centos:latest

RUN dnf update -y && \
dnf install bash gawk grep sed patch diffutils which tar cpio gzip bzip2 xz zstd unzip -y && \
dnf install gcc gcc-c++ bc bison flex libtool flex file make perl python2 python3 wget rsync ncurses-devel git -y && \
dnf install python3-six -y
