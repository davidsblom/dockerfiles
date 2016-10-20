FROM debian:testing
RUN sed -i "s/httpredir/ftp.us/" /etc/apt/sources.list
RUN apt-get clean
RUN apt-get update
RUN apt-get install -y texlive-full wget biber python aspell aspell-en aspell-nl git
