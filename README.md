# Model
The model described in this card is a classification network, which aims to classify human emotion into 6 categories.

- Neutral
- Happy
- Surprise
- Squint
- Disgust
- Scream

Primary use case for this model is to detect human emotion. The model can be used to detect human emotion from photos and videos by using appropriate video or image decoding and pre-processing. The model takes in facial landmarks as input and provide emotion classes as output.

This model needs to be used with NVIDIA Hardware and Software. For Hardware, the model can run on any NVIDIA GPU including NVIDIA Jetson devices. This model can only be used with Train Adapt Optimize (TAO) Toolkit, DeepStream 6.0 or TensorRT.
# Related Container
Use the following container to run this notebook: nvcr.io/nvidia/tao/tao-toolkit-tf:v3.21.11-tf1.15.5-py3
