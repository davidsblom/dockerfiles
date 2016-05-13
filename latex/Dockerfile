FROM debian

RUN apt-get update && apt-get install -y texlive-full xzdec wget
RUN tlmgr init-usertree
RUN tlmgr update --self --all
