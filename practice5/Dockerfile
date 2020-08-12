FROM ubuntu:latest
RUN apt-get update && apt-get install -y \
    curl \
    cvs \
    nginx
CMD ["/bin/bash"]

#CMDはDockerfileの最後に書く
#RUNはLayerを作るが、CMDはLayerを作らない。それぞれの目的を考える。
