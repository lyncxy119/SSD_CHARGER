


#模型评估->计算mAP

    python eval.py --trained_model weights/ssd.pth --voc_root C:/eval --cuda=0

#arg：voc_root为需要评估的图片路径，需要将待测图片和标注文件分别放入Image文件夹和Annotation文件夹
#绘制目标检测框

    python test.py --trained_model weights/ssd.pth --voc_root path --cuda=0

