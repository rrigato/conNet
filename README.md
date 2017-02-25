### conNet 
This repository is for using some basic convolutional neural networks


###Start by installing a docker client
[Here the link to installing on ubuntu](https://docs.docker.com/engine/getstarted/linux_install_help/)

Start up the docker container with a keras backend of Tensorflow

```
sudo docker run -d -p 8888:8888 -v /notebook:/notebook ermaker/keras-jupyter
```

By going to localhost:8888 in a browser you can view your keras jobs graphically
