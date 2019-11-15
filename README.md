# LearningToCompare_FSL
关系网络在MSTAR数据集上实现代码。

# Requirements

Python 2.7

Pytorch 0.3

# Data

MSTAR下载地址 [MSTAR](https://pan.baidu.com/s/1NcfYBEE5TdIySDDPiYOclQ). 下载完成后将数据解压到datas目录。

# Train

MSTAR 5way 4 shot:

```
python mstar_train_one_shot.py -w 5 -s 4
```

## Test

mstar 5way 4 shot:

```
python mstar_test_one_shot.py -w 5 -s 4
```


## Citing

If you use this code in your research, please use the following BibTeX entry.

```
@inproceedings{sung2018learning,
  title={Learning to Compare: Relation Network for Few-Shot Learning},
  author={Sung, Flood and Yang, Yongxin and Zhang, Li and Xiang, Tao and Torr, Philip HS and Hospedales, Timothy M},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  year={2018}
}
```


