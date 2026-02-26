
docker run --gpus all -it --rm -v $(pwd):/tf/notebooks -p 8888:8888 tensorflow/tensorflow:2.15.0-gpu-jupyter

docker run --gpus all -it -v $(pwd):/tf/notebooks -p 8888:8888 tensorflow/tensorflow:2.15.0-gpu-jupyter