FROM mcr.microsoft.com/devcontainers/universal:2-linux
RUN apt-get update && apt-get install -y curl \
    && curl -fsSL https://deb.nodesource.com/setup_16.x | bash - \
    && apt-get install -y nodejs
RUN npm install -g @vue/cli

RUN apt-get update && apt-get install -y python3 python3-pip

RUN pip3 install flask
    