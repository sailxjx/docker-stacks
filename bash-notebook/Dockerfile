# Run
# docker run -d -p 8888:8888 -v /root/42:/home/jovyan/work --name=jupyter docker-registry.teambition.net/bash-notebook start-notebook.sh --ip=*
FROM jupyter/minimal-notebook

MAINTAINER Xu Jingxin <sailxjx@gmail.com>

USER $NB_USER

RUN /opt/conda/bin/pip install --no-cache-dir bash_kernel
RUN /opt/conda/bin/python -m bash_kernel.install
