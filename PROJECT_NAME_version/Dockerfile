# docker created on the basis of Docker Hub (from hub.docker.com)
# FROM yoanlin/opencv-python3-tensorflow
FROM jjanzic/docker-python3-opencv

# install jupyter lab
RUN pip3 install jupyterlab

# install ML and DL libraries
RUN python -m pip install -U matplotlib
# RUN pip3 install --upgrade tensorflow
# RUN pip3 install torch torchvision
# RUN pip3 install keras


ENTRYPOINT ["jupyter", "lab"]
