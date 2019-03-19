SUMMARY
===
| model | input size | param mem | feat. mem | flops  |
|-------|------------|--------------|----------------|-------------|
| resnet-50 | 224 x 224 | 98 MB | 103 MB | 4 BFLOPs |
| resnet-152 | 224 x 224 | 230 MB | 219 MB | 11 BFLOPs |
| inception-v3 | 299 x 299 | 91 MB | 89 MB | 6 BFLOPs |
| vgg-vd-19 | 224 x 224 | 548 MB | 63 MB | 20 BFLOPs |
| alexnet | 227 x 227 | 233 MB | 3 MB | 1.5 BFLOPs |
| ssd-300 | 300 x 300 | 100 MB | 116 MB | 31 GFLOPS |


**syn-replicated-fp32-1gpus**

Config | 2950X-GeForce_RTX_2080_Ti |
:------:|:------:|
resnet50 | |
resnet152 | |
inception3 | |
inception4 | |
vgg16 | |
alexnet | |
ssd300 | |


**syn-parameter_server-fp32-1gpus**

Config | 2950X-GeForce_RTX_2080_Ti |
:------:|:------:|
resnet50 | |
resnet152 | |
inception3 | |
inception4 | |
vgg16 | |
alexnet | |
ssd300 | |


**syn-replicated-fp16-1gpus**

Config | 2950X-GeForce_RTX_2080_Ti |
:------:|:------:|
resnet50 | |
resnet152 | |
inception3 | |
inception4 | |
vgg16 | |
alexnet | |
ssd300 | |


**syn-parameter_server-fp16-1gpus**

Config | 2950X-GeForce_RTX_2080_Ti |
:------:|:------:|
resnet50 | |
resnet152 | |
inception3 | |
inception4 | |
vgg16 | |
alexnet | |
ssd300 | |
