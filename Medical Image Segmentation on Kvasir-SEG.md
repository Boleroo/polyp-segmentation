





paper

#### Colorectal polyp region extraction using saliency detection network with neutrosophic enhancement

https://www.webofscience.com/wos/woscc/full-record/WOS:000861569700004

https://www.sciencedirect.com/science/article/pii/S0010482522005340

**idea:**

- 图像处理：镜面抑制反射，图像修复

![image-20230602125300812](C:\Users\余成远\AppData\Roaming\Typora\typora-user-images\image-20230602125300812.png)

- 显著性区域检测

  多尺度特征融合

  基于VGG网络，每个阶段侧网络引入短链接

**dataset:**

EndoScene( CVC-ColonDB + CVC-ClinicDB) 和Kvasir-SEG

**result**

![image-20230602133647165](C:\Users\余成远\AppData\Roaming\Typora\typora-user-images\image-20230602133647165.png)

![image-20230602133656101](C:\Users\余成远\AppData\Roaming\Typora\typora-user-images\image-20230602133656101.png)



#### EMS-NET（2021，EMBC）粗粒度息肉分割的增强型多尺度网络

以Unet++为baseline

RFB模块：多尺度跳跃连接，多尺度特征

LCA上下文注意模块：精确息肉边界分割

![image-20230602145500332](C:\Users\余成远\AppData\Roaming\Typora\typora-user-images\image-20230602145500332.png)





https://ieeexplore.ieee.org/mediastore_new/IEEE/content/media/9629355/9629471/9630787/wang.t3-p4-wang-large.gif



#### **用于息肉分割和分类的高效多任务协同网络**（2023，JBHI）

![image-20230602150953731](C:\Users\余成远\AppData\Roaming\Typora\typora-user-images\image-20230602150953731.png)

分割+分类

- EMS-Net 获得粗分割掩码

- EMS-Net得到的mask与结肠镜图像连接，帮助 EMTS-Net (Class) 精确定位和分类息肉

- 提出了一种随机多尺度（RMS）训练策略，RMS结合class分类，消除冗余信息，帮助 EMTS-Net (Seg)执行更准确的息肉分割

  ![image-20230602151353941](C:\Users\余成远\AppData\Roaming\Typora\typora-user-images\image-20230602151353941.png)

  

#### Polyp-Net: A Multimodel Fusion Network for Polyp Segmentation

code

BDGnet

https://github.com/zihuanqiu/BDG-Net

SSFormer

https://github.com/Qiming-Huang/ssformer