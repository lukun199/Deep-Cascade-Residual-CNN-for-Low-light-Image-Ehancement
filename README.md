# Deep-Cascade-Residual-CNN-for-Low-light-Image-Ehancement
In this project, we explored a new deep cascade residual CNN which is designed for low-level Image-Enhancement tasks, where this framework is now tested in the low-light Image ehancement environment. This framework is composed of several detachable Sub-U_net , which takes both the high-level and low-level features as its input so as to generate a fine low-light image. In the middle-scale experiment, we fond that this network had already outperformed the vast majoryt of the model and achieved the SOTA results. Moreover, our ntework significantly reduces the total paremeters compared with several methods proposed in 2018 and 2019. We suppose this network structure could also be used in other low-level image enhancement tasks.

Since we are still working in this project, we would not release our source code till publication. The ablation experiments are now undergoing.  
     
However, some the enhanced low-light imagses is available here.   
     
Note that because of the RAM limitation of this machine (8G), the ‘5.bmp’ could not be processed, and that's why we give the results of the remaining 9 images.  
     
Still, this result is yield in a middle-scale test. As we see that some artifacts do exist in some testing samples, such as the ‘9.bmp’. This is mainly caused by insuffucient trainning and limited dataset (GTX 1060, 25 hours with only 1800+ training images). We will perfect this model in around 2 months.

SEE THE RESULTS BELOW.
![image](https://github.com/lukun199/Deep-Cascade-Residual-CNN-for-Low-light-Image-Ehancement/raw/1.bmp)
![image](https://github.com/lukun199/Deep-Cascade-Residual-CNN-for-Low-light-Image-Ehancement/enhanced/1_out.bmp)
