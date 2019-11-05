Person search
===============

<img src="show.jpg" width="900px"/>

## Dependencies

Tested under python3.7  MacOS 10.14.6

- python packages
  - opencv-python
  - tb-nightly
  - torch >= 1.0

## Download weights
Download from [here](https://pan.zju.edu.cn/share/09919f945ae2fd0d03d45f4010)

After download, put the weights into the floder **person_search_demo/weights**

Test
--------

```bash
cd <path to this floder>
python search.py
```

The results will be saved in the output folder

## Train

Pedestrian detection model is YOLOv3 code, so you can directly use the original [YOLO](https://link.zhihu.com/? Target=https%3A//github.com/ultralytics/yolov3) code for training, get the weight file.

Pedestrian re-identification model is adopted [strong Reid baseline](https://link.zhihu.com/? Target=https%3A//github.com/michuanhaohao/reid-strong-baseline) model, but in order to achieve better generalization effect, can be more joint training data set, get the final weight file.

