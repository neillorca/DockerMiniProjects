FROM docker/whalesay
RUN apt-get update -y -qq
RUN apt-get install -y -qq fortunes
CMD /usr/games/fortune -a | cowsay