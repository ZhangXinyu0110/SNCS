# Spacecraft Normalized Coordinate Space for Pose and Size Estimation of Unknown Space Targets
![image](https://github.com/ZhangXinyu0110/SPSE/blob/main/framework1.png)

## abstract
 Noncooperative Spacecraft pose estimation is vital for numerous space missions. Recently, data-driven methods for spacecraft pose estimation have attracted growing interest. However, existing methods rely on offline training using prior models of specific spacecraft types, limiting pose estimation to specific types and failing to handle unknown spacecraft during training. To address these issues, we propose a Spacecraft Normalized Coordinate Space (SNCS) as a unified geometric representation across spacecraft models. When dealing with unknown targets, we learn target-specific Shape Deformation Residuals (SDR) based on observed point clouds to transform SNCS into a reference model encoding the object’s rotation information, and complete the full target shape from single-view point clouds using symmetry cues, enabling pose and size estimation for unknown spacecraft. Additionally, to better evaluate out-of-distribution generalization to unknown spacecraft, we constructed and released a pose and size estimation dataset containing 33 spacecraft types as a benchmark for universal spacecraft pose estimation tasks. Comprehensive experiments demonstrate that our method effectively adapts to significant shape variations among targets, showing good estimation accuracy, fast response, and cross-model generalization ability for unknown targets.

## SPSED DATASETS
The SPSED dataset is coming soon
