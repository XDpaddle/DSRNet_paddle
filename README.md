# Dsrcnn_paddle

## Image super-resolution via dynamic network

Paddle 复现版本

## 数据集

DIV2K
## 训练步骤
### train sr
```bash
python train.py -opt config/train/train_dsrcnn_xx.yml
```
## 测试步骤
```bash
python test.py -opt config/test/test_dsrcnn_xx.yml
```