FROM debian

RUN apt-get update && apt-get install -y texlive-full xzdec wget biber
RUN tlmgr init-usertree
RUN tlmgr update --self --all
