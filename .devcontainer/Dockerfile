FROM mcr.microsoft.com/devcontainers/python:1-3.12-bookworm

COPY requirements.txt /tmp/requirements.txt

RUN apt-get update && apt-get install -y curl wget bash-completion

USER vscode
RUN pip install --no-cache --user -U pip -r /tmp/requirements.txt