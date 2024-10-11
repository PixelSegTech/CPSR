# Class Probability Space Regularization for semi-supervised semantic segmentation
 Abstract:—Semantic segmentation achieves fine-grained scene parsing in any scenario, making it one of the key research directions to facilitate the development of human visual attention mechanisms. Recent advancements in semi-supervised semantic segmentation have attracted considerable attention due to their potential in leveraging unlabeled data. However, existing methods only focus on exploring the knowledge of unlabeled pixels with high certainty prediction. Their insufficient mining of low certainty regions of unlabeled data results in a significant loss of supervisory information. Therefore, this paper proposes the Class Probability Space Regularization (CPSR) approach to further exploit the potential of each unlabeled pixel. Specifically, we first design a class knowledge reshaping module to regularize the probability space of low certainty pixels, thereby transforming them into high certainty ones for supervised training. Furthermore, we propose a tail probability suppression module to suppress the probabilities of tailed classes, which facilitates the network to learn more discriminative information from the class probability space. Extensive experiments conducted on the PASCAL VOC2012 and Cityscapes datasets prove that our method achieves state-of-the-art performance without introducing much computational overhead.

 # Pipeline
 ![Network](https://github.com/PixelSegTech/CPSR/blob/main/Net.png)

 # Citation
 If you find this project useful, please consider citing:

 > @article{yin2024class, <br>
  title={Class Probability Space Regularization for semi-supervised semantic segmentation}, <br>
  author={Yin, Jianjian and Yan, Shuai and Chen, Tao and Chen, Yi and Yao, Yazhou}, <br>
  journal={Computer Vision and Image Understanding}, <br>
  pages={104146}, <br>
  year={2024},  <br>
  publisher={Elsevier}  <br>
}

