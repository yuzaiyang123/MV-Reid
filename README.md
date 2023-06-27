# MV-Reid: 3D Multi-View Transformation Network for Occluded Person Re-Identification 

Thanks for your attention. In this repo, we provide the code and dataset for the paper "MV-Reid: 3D Multi-View Transformation Network for Occluded Person Re-Identification".



# Open-source  schedule


**15 Feb 2023.** Open source the subset of the multi-view-Occluded-ReID.  [Google drive](https://drive.google.com/file/d/16AiRXShlsCyFC5ilCuw_HqIburIuvnMv/view) **[Done]**




 Multi-view-duke, Multi-view-Occluded-duke and MV-Reid source code will be open source after this paper is accepted.



# Dataset introduction

A reconstruct algorithm SMPL and a rendering engine blender are adopted to generate multi-view dataset from input images in this work. Exactly, we present four large-scale 3D multi-view person ReID datasets.

The scale of Multi-view-Market1501, Multi-view-duke,  Multi-view-Occluded-duke and  Multi-view-Occluded-ReID  as shown:

<!-- **The data scale of the Multi-duke in the manuscript is wrong. At present, the manuscript is under review, so we cannot update the Table 1 in the manuscript. We firstly modify the error content in the table in github, and then we will update the Table 1 in the manuscript.** -->


| Dataset          |              | #ID   | #3D model | #Multi-view image |
| ---------------- | ------------ | ----- | --------- | ----------------- |
| MV-Market-1501   | Training     | 751   | 129,36    | 155,232           |
|           | Gallery              | 752   | 197,32    | 236,784           |
|             | Query              | 750   | 3368      | 40,416            |
| MV-duke          | Training Set | 702   | 16,522    | 198,264           |
|           | Gallery              | 1,110 | 17,661    | 211,932           |
|             | Query              | 702   | 2228      | 26,736            |
| MV-Occluded-duke | Training     | 702   | 15,618    | 187,146           |
|           | Gallery              | 1,110 | 17,661    | 211,932           |
|             | Query              | 519   | 2210      | 26,520            |
| MV-Occluded-ReID | Training     | -   | -    | -           |
|           | Gallery              | 200 | 200    | 12,000           |
|             | Query              | 200 | 200    | 12,000           |




We Visualize the subset of MV-Market-1501

![image](https://github.com/yuzaiyang123/MV-Reid/blob/main/fig-5.jpg)
