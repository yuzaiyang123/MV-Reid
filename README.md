# MV-Reid: 3D Multi-View Transformation Network for Occluded Person Re-Identification 

Thanks for your attention. In this repo, we provide the code and dataset for the paper "MV-Reid: 3D Multi-View Transformation Network for Occluded Person Re-Identification".



# Open-source  schedule

**07 Jul 2022.** Open source the query of multi-view-market1501. You can directly download my generated 3D multi-view data of the multi-view-market1501 dataset at  [Google drive](https://drive.google.com/file/d/1RvsWy69LtjCbJJkpSD8DeOXqA2Kmkv28/view?usp=sharing)

**15 Sept 2022.** Open source the gallery of multi-view-market1501. 

**15 Nov 2022.** Open source the complete multi-view-market1501. 

Another dataset multi-view-duke and MV-Reid source code will be open source after this paper is accepted.



# Dataset introduction

Multi-view-Market1501 and Multi-view-duke are derived from Market1501 and occluded-duke.  A reconstruct algorithm SMPL and a rendering engine blender are adopted to generate multi-view dataset from input images in this work. Exactly, the original images of Market1501 and occluded-duke are firstly reconstruct to 3D model, and then rendering to 12 view images.

The scale of Multi-view-Market1501 and Multi-view-duke  as shown:

| Dataset        |              | #ID   | #3D model | #Multi-view image |
| -------------- | ------------ | ----- | --------- | ----------------- |
| MV-Market-1501 | Training Set | 751   | 129,36    | 155,232           |
|                | Gallery      | 752   | 197,32    | 236,784           |
|                | Query        | 750   | 3368      | 40,416            |
| MV-duke        | Training Set | 702   | 15,618    | 187,146           |
|                | Gallery      | 1,110 | 17,661    | 211,932           |
|                | Query        | 519   | 2210      | 26,520            |



We Visualize the subset of MV-Market-1501

![image](https://github.com/yuzaiyang123/MV-Reid/blob/main/fig-5.jpg)
