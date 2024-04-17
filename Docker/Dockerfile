FROM pytorch/pytorch:2.2.2-cuda12.1-cudnn8-devel
RUN apt update && apt upgrade -y
RUN apt install -y wget zip unzip
RUN python3 -m pip install --upgrade pip
RUN python3 -m pip install tqdm opencv-python torchfile
RUN python3 -m pip install Pillow==9.5.0
RUN mkdir /style-transfer
WORKDIR /style-transfer
