# SPSE: Pose and Size Estimation of Non-Cooperative Spacecraft via Category-Level Normalized Reference Frame
![image](https://github.com/ZhangXinyu0110/SPSE/blob/main/framework.png)

## abstract
In recent years, deep learning-based pose estimation methods have attracted increasing attention. However, due to the scarcity of real-world space data, it remains challenging for researchers to obtain large-scale, real-world training datasets with accurate pose annotations.

To address this issue, we propose a pose and size estimation method that does not rely on externally annotated real-world training data. Our method is capable of performing 6D pose and size estimation directly from the point cloud of a target spacecraft in a single scene. The core idea of our approach is to leverage the shape models of previously launched spacecraft to construct category-level normalized reference frames. These reference frames are then deformed to align with the observed point cloud, implicitly representing the target's 3D rotation. To further handle occlusion issues from single-view observations, we introduce shape completion based on the symmetry priors of each category, yielding a more complete reconstruction of the target. This enhances the accuracy of translation and size estimation. 

In addition, we construct a Spacecraft Pose and Size Estimation Dataset (SPSED) consisting of 33 types of spacecraft, which is used to train and evaluate the proposed method. Comprehensive experiments demonstrate that our approach effectively adapts to significant shape variations among targets, achieving high pose estimation accuracy, fast inference speed, and strong generalization to unseen instances. 

## SPSED DATASETS
The SPSED dataset is coming soon
