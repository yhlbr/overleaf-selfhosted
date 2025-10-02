# Build from scratch:
# cd ../server-ce
# docker build -f Dockerfile-base -t sharelatex/sharelatex-base:latest .
# docker build -f Dockerfile -t sharelatex/sharelatex:latest ..
FROM sharelatex/sharelatex

RUN tlmgr update --self
RUN tlmgr install scheme-full