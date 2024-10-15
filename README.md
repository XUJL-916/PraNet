# PraNet: Parallel Reverse Attention Network for Polyp Segmentation (MICCAI2020-Oral)

> **Authors:** 
> [XUJL](https://github.com/XUJL-916/PraNet), 

### 目录
一. [仓库更新 Top News](#仓库更新)
二. [相关仓库 Related code](#相关仓库)
三. [性能情况 Performance](#性能情况)
四. [所需环境 Environment](#所需环境)
五. [文件下载 Download](#文件下载)
六. [训练步骤 How2train](#训练步骤)
七. [预测步骤 How2predict](#预测步骤)
八. [评估步骤 miou](#评估步骤)
九. [参考资料 Reference](#Reference)


一. [仓库更新 Top News](#仓库更新)

1. 20241014 创建该仓库


二. [相关仓库 Related code](#相关仓库)



三. [性能情况 Performance](#性能情况)

四. [所需环境 Environment](#所需环境)
1. 环境安装步骤 (Python 3.10 + cuda 12.1) Anaconda 环境配置
    1.1 新建一个新的环境 conda create --name PraNet python==3.10
    1.2 安装一些对应包 --r requriements.txt
    1.3 安装cuda以及pytorch,根据电脑型号选择
    示例:conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
    1.4 验证是否安装成功
    python -c "import torch; print(torch.cuda.is_available())"
    1.5 安装依赖库conda install numpy scipy matplotlib jupyter
    1.6 保存环境导出环境conda env export > PraNet.yml
    conda env create -f PraNet.yml
五. [文件下载 Download](#文件下载)
数据集下载网址:

    
六. [训练步骤 How2train](#训练步骤)


七. [预测步骤 How2predict](#预测步骤)


八. [评估步骤 miou](#评估步骤)



九. [参考资料 Reference](#Reference)


十. [遇到的问题以及解决方案](#Questions&solutions)



































