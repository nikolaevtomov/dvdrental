FROM jupyter/datascience-notebook

WORKDIR /home/jovyan/work
COPY requirements.txt /home/jovyan/work/
RUN pip3 install -r requirements.txt
COPY . /home/jovyan/work/