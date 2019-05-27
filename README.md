# Deep-Cascade-Residual-CNN-for-Low-light-Image-Ehancement
In this project, we explored a new deep cascade residual CNN which is designed for low-level Image-Enhancement tasks. It is now tested in the low-light Image ehancement task. The framework is composed of several detachable Sub-U_nets, where both the high-level and low-level features are taken as its input to jointly enhance the details and global styles in an image. A global-regional detail module is further introduced to facilitate the learning of detailed features. In the small-scale experiment(30th, April), we found that this network had already achieved a competitive results. Moreover, our network has relatively fewer paremeters compared with many methods proposed in 2018 and 2019. We suppose this network structure could also be used in other low-level image enhancement tasks.

Since we are still working on this project, we would not release our source code and metwork framework till better results yield and publication in the future. More experiments are now undergoing.  
     
However, some of the enhanced low-light imagses are shown here.   
       
           
The results of our cascade structure are shown below.  
![cascade_structure](Eval/structure.png)  

   
The test images used here are cited from LIME,Cai,BIMEF,DICM,VV,MEF,NPE,LOL...  
(https://github.com/baidut/BIMEF  https://daooshee.github.io/BMVC2018website/ https://github.com/csjcai/SICE).  

SEE THE RESULTS BELOW.  
* Quantitive evaluation  (We added the 'NIQE' index in 05/28/2019, rank 1st, not shown)
![Q_eval](Eval/Quantitive_Evaluation.png)
       
* Visual evaluation   
Images from Cai-1E dataset
![V_eval](Eval/Visual_Evaluation.png)
           
Images from LIME dataset  
![v2_eval](Eval/v_2.png)

Our enhanced images are provided. If you can not preview these images , please feel free to download the raw images above.
