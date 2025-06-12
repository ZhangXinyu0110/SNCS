# CSPE-NET: Pose Estimation for  Non-Cooperative Spacecraft  Without CAD Priors via  Normalized Reference Frame
![image](https://github.com/ZhangXinyu0110/CSPE-NET/blob/main/CSPE%20NET.png)
## abstract
Pose estimation of non-cooperative spacecraft is crucial for a range of space missions. However, existing methods typically rely on the CAD models of target objects as prior information, either for offline training or online template matching. This reliance limits the applicability and generalizability of pose estimation algorithms.

To address the limitations of existing methods, which rely on prior knowledge of the target model and exhibit poor generalization capabilities, this work proposes a novel pose estimation approach for non-cooperative spacecraft that does not require model priors. Instead, it utilizes a normalized reference frame derived from historical real spacecraft models. Specifically, we first categorize existing spacecraft models and extract a category-level normalized reference frame. We then introduce CNRF-NET, a network designed to predict a normalized reference frame aligned with the instance shape, thereby implicitly encoding rotational information. Finally, based on the network predictions, the target’s 6D pose and 3D size are recovered from the aligned reference frame.

In addition, this paper introduces the CSPED dataset for spatial pose estimation, which comprises 33 spacecraft models and is used to train and evaluate the proposed method. Extensive experiments demonstrate that the method effectively handles substantial intra-class shape variations and can accurately estimate the poses of previously unseen targets within the same category, without the need for retraining.

## CSPED DATASETS
The CSPED dataset is coming soon
