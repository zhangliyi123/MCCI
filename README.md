## MCCI
This code enhances task diversity through multi-task convex combination interpolation, thereby improving the generalization capability of meta-learning models.


## Dependence
* python 3.7
* Pytorch 1.5+

## Usage
python main.py --datasource=xx --metatrain_iterations=xx --meta_lr=xx --meta_batch_size=xx --update_batch_size=xx --update_batch_size_eval=xx --num_classes=xxx --datadir='./data/' --logdir=xx --mix=xx
python main.py --datasource=xx --metatrain_iterations=xx --meta_lr=xx --meta_batch_size=xx --update_batch_size=xx --update_batch_size_eval=xx --num_classes=xxx --datadir='./data/' --logdir=xx --mix=xx --train=xx --test_epoch=xx

## About
1.This code and dataset are based on the paper [Meta-Learning with Fewer Tasks through Task Interpolation](https://arxiv.org/abs/2106.02695).
2.Dataset: [Google Drive](https://drive.google.com/drive/folders/1MG881Zjh1vaWd3dizhYH_l5APXEiKZrx?usp=sharing)
If you find this repository useful in your research, please cite the following paper:

```
@inproceedings{yao2022meta,
  title={Meta-Learning with Fewer Tasks through Task Interpolation},
  author={Yao, Huaxiu and Zhang, Linjun and Finn, Chelsea},
  booktitle={Proceeding of the 10th International Conference on Learning Representations},
  year={2022} 
}
```
### Contact Information:
If you find any errors or have any questions, please feel free to contact me. I am very willing to communicate and learn from everyone. My email address is: 1404945515@qq.com.
