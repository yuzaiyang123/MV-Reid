# MV-Reid: 3D Multi-View Transformation Network for Occluded Person Re-Identification 

Thanks for your attention. In this repo, we provide the code and dataset for the paper "MV-Reid: 3D Multi-View Transformation Network for Occluded Person Re-Identification".



# Open-source  schedule

**07 Jul 2022.** Open source the query of multi-view-market1501. You can directly download my generated 3D multi-view data of the multi-view-market1501 dataset at  [Google drive](https://drive.google.com/file/d/1RvsWy69LtjCbJJkpSD8DeOXqA2Kmkv28/view?usp=sharing)

**15 Oct 2022.** Open source the query of multi-view-duke. 

**15 Nov 2022.** Open source the query of multi-view-Occluded-duke. 

**15 Feb 2023.** Open source the complete multi-view-market1501. 

 Multi-view-duke, Multi-view-Occluded-duke and MV-Reid source code will be open source after this paper is accepted.



# Dataset introduction

A reconstruct algorithm SMP and a rendering engine blender are adopted to generate multi-view dataset from input images in this work. Exactly, we presents three large scale 3D multi-view person ReID datasets, Multi-view-Market1501, Multi-view-duke and  Multi-view-Occluded-duke, which are derived from Market1501, Dukemtmc and Occluded-duke, respectively. Our datasets provide new ways of thinking to resolve occluded person ReID.

The scale of Multi-view-Market1501, Multi-view-duke and  Multi-view-Occluded-duke  as shown:

| Dataset          |              | #ID   | #3D model | #Multi-view image |
| ---------------- | ------------ | ----- | --------- | ----------------- |
| MV-Market-1501   | Training     | 751   | 129,36    | 155,232           |
| Gallery          |              | 752   | 197,32    | 236,784           |
| Query            |              | 750   | 3368      | 40,416            |
| MV-duke          | Training Set | 702   | 15,618    | 187,146           |
| Gallery          |              | 1,110 | 17,661    | 211,932           |
| Query            |              | 519   | 2210      | 26,520            |
| MV-Occluded-duke | Training     | 702   | 15,618    | 187,146           |
| Gallery          |              | 1,110 | 17,661    | 211,932           |
| Query            |              | 519   | 2210      | 26,520            |

Note that because the Occluded-duke derived from the Dukemtmc, so the scale of Multi-view-duke is equal to Multi-view-Occluded-duke. 


We Visualize the subset of MV-Market-1501

![image](https://github.com/yuzaiyang123/MV-Reid/blob/main/fig-5.jpg)
