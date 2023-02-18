FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0-18

RUN export DEBIAN_FRONTEND=noninteractive && \
    apt-get update && \
    apt-get upgrade -y && \
    apt-get autoremove -y

RUN yarn global add @vscode/vsce