# pointnet

## environment

torch >= 1.1.0

## 已训练模型

链接: https://pan.baidu.com/s/11KKvBtmubQPrUg7o587PsQ 提取码: 4r79

## 训练
cd pointnet_gpu
python train_cls.py --batch_size 256 --model pointnet_cls --epoch 200 --gpu 0 --normal False 


## 测试
cd pointnet_gpu
python test_cls.py #需要将checkpoint放到指定位置
