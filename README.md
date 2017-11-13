# MXNet SSD

This is the mxnet version of ssd, maintained by myself and modified some codes compare to the official one. This is my result trained on resnet50:

<center>![](https://i.loli.net/2017/11/13/5a0911652bfb0.jpg)</center>

<center>![](https://i.loli.net/2017/11/13/5a09118e78e29.jpg)</center>

<center>![](https://i.loli.net/2017/11/13/5a0911f0ebd37.jpg)</center>

And the speed is  0.1 seconds on GTX1080 Ti with cudnn enabled.

## Try it

To quickly try this demo, you should download the official repo ssd_resnet50_512 model. and directly run:

```
python3 demo.py --images=/path/to/your/image/dir
```

and you will get fair results.



## Train

For training, just run `python3 train.py --help` for more detail, you probably should learn how to generate .rec file for detection.



## Copyright

this repo is original write by mxnet official, this is a fork version maintained by Jin Fagang.

