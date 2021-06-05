# ANRN

# Angle-Based Non-local Recurrent Network for Single Image Deraining

Implementation detail for our paper "Angle-Based Non-local Recurrent Network for Single Image Deraining"
(https://ieeexplore.ieee.org/abstract/document/9344890), this code also includes further resaerch beyound this paper.

## Citation

Please cite this paper in your publications if it helps your research:

```
@INPROCEEDINGS{9344890,  author={Wang, Zefan and Zhu, Chuang and Liu, Jun and Lin, WenHui and Liu, YaTing and Li, Chunxu},  
booktitle={2020 IEEE 6th International Conference on Computer and Communications (ICCC)},   
title={Angle-Based Non-local Recurrent Network for Single Image Deraining},  
year={2020},  volume={},  number={},  
pages={2261-2264}, 
doi={10.1109/ICCC51575.2020.9344890}}
```

## Dataset
Rain100H:
Rain100L:

If you have questions regarding the patch dataset (with or without noisy labels, please contact us: wangzefan@bupt.edu.cn)

## Envs
- Pytorch 1.0
- Python 3+
- cuda 9.0+

## Training
```
$ cd code/
# train dataset and record training history
$ sh train.sh
# test dateset and record test results
$ sh test.sh
# use ssim.py to calculate SSIM 
$ python ssim.py

```
## Contact

* email：wangzefan@bupt.edu.cn; czhu@bupt.edu.cn
* qq: 466123174
