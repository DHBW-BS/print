FROM ubuntu:latest

RUN "wget https://www.nasm.us/pub/nasm/releasebuilds/2.16.03/nasm-2.16.03.tar.gz"
RUN "tar xvfz nasm-2.16.03.tar.gz"
RUN "cd nasm-2.16.03 && configure --prefix /opt/local && make install"
RUN "rm -rf nasm-2.16.03.tar.gz nasm-2.16.03"
