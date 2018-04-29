# SIFT-GPU
A CUDA implementation of SIFT：<https://github.com/amusi/SIFT-GPU>



# 配置

（待完成）见SIFT-GPU配置教程





# 测试

**1.Release 模式**

```shell
cd bin
./SimpleSIFT.exe
```

Release模式，输出结果：

[SiftGPU Language]:     GLSL
[GPU VENDOR]:   NVIDIA Corporation 1717MB
TEXTURE:        16384
Image size :    800x600
Image loaded :  ../data/800-1.jpg

Features:      3358

Features MO:   3923

[RUN SIFT]:     0.189

Image size :    640x480
Image loaded :  ../data/640-1.jpg

Features:      2383

Features MO:   2791

[RUN SIFT]:     0.066

[SiftMatchGPU]: GLSL

2279 sift matches were found;



**2.Debug 模式**

```shell
.\SimpleSIFT_d.exe
```





# 参考

Changchang Wu：http://cs.unc.edu/~ccwu

<https://github.com/pitzer/SiftGPU>