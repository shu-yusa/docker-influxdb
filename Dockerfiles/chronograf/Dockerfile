FROM chronograf:latest

RUN apt-get update
RUN apt-get install -y vim
ADD vimrc /root/.vimrc
RUN echo "alias ls='ls -hp'" >> /root/.bashrc
RUN echo "alias ll='ls -l'" >> /root/.bashrc
RUN echo "alias la='ls -la'" >> /root/.bashrc
