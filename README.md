## Getting started

#### Conda (Recommended)

```bash
# Tensorflow CPU
conda env create -f conda-cpu.yml
conda activate yolov3-cpu

# Tensorflow GPU
conda env create -f conda-gpu.yml
conda activate yolov3-gpu
```

#### Pip
```bash
# TensorFlow CPU
pip install -r requirements.txt

# TensorFlow GPU
pip install -r requirements-gpu.txt
```

#### !ATTENTION: BEFORE RUNNING THE APP, PLEASE PUT THE WEIGHT IN "weights" FOLDER FIRST, AND RENAME IT yolov3.weights, OTHERWISE YOU WILL HAVE TO CONFIG THE PATH TO WEIGHT IN APP.PY

#### Running
```bash
python app.py
```
The weight are preload before starting server.
App will run on port 5000.
#### If you prefer to load the weight first, run:
```bash
load_weights.py
```
