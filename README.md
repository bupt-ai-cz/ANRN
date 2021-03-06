# ANRN [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Codes%20and%20Data%20for%20Our%20Paper:%20"Angle-Based%20Non-local%20Recurrent%20Network%20for%20Single%20Image%20Deraining"%20&url=https://github.com/bupt-ai-cz/ANRN)

# Angle-Based Non-local Recurrent Network for Single Image Deraining

Implementation detail for our paper [Angle-Based Non-local Recurrent Network for Single Image Deraining](https://www.researchgate.net/publication/349280836_Angle-Based_Non-local_Recurrent_Network_for_Single_Image_Deraining), this code also includes further resaerch beyound this paper.

## Dataset

Download these datasets to code/datasets

Rain100H and Rain100L: 
[Google Drive](https://drive.google.com/drive/folders/1sF_2hNvz-6yoNJCxq8aa5oN3yz0VvsjQ?usp=sharing) or [Baidu YUN](https://pan.baidu.com/s/1J0q6Mrno9aMCsaWZUtmbkg#list/path=%2F)

If you have questions regarding the dataset (please contact us: wangzefan@bupt.edu.cn, czhu@bupt.edu.cn)

## Envs
- Pytorch 1.0
- Python 3+
- cuda 9.0+

## Training
```
$ cd code/
# train network
$ sh train.sh
# test dateset and record test results
$ sh test.sh
# use ssim.py to calculate SSIM 
$ python ssim.py

```

## Citation

Please cite this paper in your publications if it helps your research:

```
@inproceedings{wang2020angle,
  title={Angle-Based Non-local Recurrent Network for Single Image Deraining},
  author={Wang, Zefan and Zhu, Chuang and Liu, Jun and Lin, WenHui and Liu, YaTing and Li, Chunxu},
  booktitle={2020 IEEE 6th International Conference on Computer and Communications (ICCC)},
  pages={2261--2264},
  year={2020},
  organization={IEEE}
}
```

Please also cite the following paper if you use the dataset:

Yang W, Tan R T, Feng J, et al. Deep joint rain detection and removal from a single image[C]. Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2017: 1357-1366.


## Contact

* email：wangzefan@bupt.edu.cn; czhu@bupt.edu.cn
* qq: 466123174
