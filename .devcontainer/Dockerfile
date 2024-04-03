FROM mcr.microsoft.com/devcontainers/base:ubuntu-22.04

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install python3-pip git-buildpackage debmake debhelper-compat dh-python pybuild-plugin-pyproject python3-all \
    && pip3 install --upgrade poetry