# SMA-Net
Pedestrian detection is of great significance due to its wide application in various fields. RGB-T based pedestrian detection has received more extensive attention due to the provided detailed information and thermal sensitivity of pedestrians. However, the existing RGB-T based methods focus on the fused features, while ignoring the robustness and superiority of the extracted features from each single modality. In this paper, a single-modal feature augment network (SMA-Net) is proposed to enhance the features extracted from each branch before feature fusion. Firstly, two single-modal branches are trained separately to optimize the feature extraction of each branch in addition to the training of pedestrian detection based on fused features. To further enhance the single-modal features, fake feature maps generated by random noise are used to combine with the RGB or thermal feature maps. Secondly, a lightweight ROI pooling multiscale fusion module (PMSF) is proposed to obtain more fine-grained and abundant features, in which pooling features of different scales are integrated by adaptively weighting. Finally, a generative constraint strategy is designed to constrain fusion by minimizing the loss function between the generated fusion image and RGB-T pairs. Experimental results on the challenging KAIST multispectral pedestrian dataset demonstrate that the proposed SMA-Net outperforms the state-of-the-art methods in terms of accuracy and computational efficiency.
# Detection Result.
our detection results are available, called result.rar.
# The code will be available after we sort out it.
