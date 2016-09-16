FROM debian:testing
RUN sed -i "s/httpredir/ftp.us/" /etc/apt/sources.list
RUN apt-get clean && apt-get update && apt-get install -y texlive-full xzdec wget biber python aspell aspell-en aspell-nl git
