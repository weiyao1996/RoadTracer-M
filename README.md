# RoadTracer-M

This repository is the official implementation of [ROAD NETWORK EXTRACTION FROM SATELLITE IMAGES USING CNN BASED SEGMENTATION AND TRACING](https://ieeexplore.ieee.org/abstract/document/8898565).  It aims at tracking the road centerline from multiple starting points in satellite images.

## Pipeline 

![image-20200728150157771](README.assets/image-20200728150157771.png)

## Results

![image-20200728150255134](README.assets/image-20200728150255134.png)


## Requirements

To install requirements:

```setup
pip install -r requirements.txt
```

>📋 For generating the **dataset**, please refer to [RoadTracer](https://github.com/mitroadmaps/roadtracer) for more details.

## Training

To train the model(s) in the paper, run this command:

```train
python train.py --input-data <path_to_data> --alpha 10 --beta 20
```

>📋  Describe how to train the models, with example commands on how to train the models in your paper, including the full training procedure and appropriate hyperparameters.


## Contributing

- [yao WEI]()
- [kai ZHANG]()