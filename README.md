# detect-doors

Install tensorflow object detection models before using.

Clone model

`git clone https://github.com/tensorflow/models`

Clone dataset

`!pip install -q kaggle`

`!pip install -q kaggle-cli`

Set credientials

`import os`

`os.environ['KAGGLE_USERNAME'] = 'your-username'`

`os.environ['KAGGLE_KEY'] = 'your-key'`

Install dataset

`%%bash`
`mkdir /content/dataset`

`cd /content/dataset`

`kaggle datasets download -d deepaksuthr/datadoor --unzip`

Download SSDResNet50 V1
[Download](http://download.tensorflow.org/models/object_detection/tf2/20200711/ssd_resnet50_v1_fpn_640x640_coco17_tpu-8.tar.gz)

Download and extract it inside pre-trained-models
