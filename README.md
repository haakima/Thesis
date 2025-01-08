Title: Single-shot uncertainty estimation in artificial neural networks using ensemble classes
 
Uncertainty estimation is a critical factor in the deployment of artificial neural networks (ANNs) in high-stakes applications such as autonomous driving and medical diagnostics, where the ability to quantify model confidence is as essential as predictive accuracy. Traditional ensemblebased uncertainty estimation methods, such as Deep Ensembles and Monte Carlo Dropout, have demonstrated efficacy in improving model robustness and uncertainty calibration. However, these methods typically require multiple forward passes, resulting in increased latency and energy consumption, making them impractical for real-time, resource-constrained environments. This thesis introduces the Class Ensemble method, which addresses these limitations by ensembling neurons within the final layer of the network while sharing a common feature extraction backbone. This novel approach enables single-shot uncertainty estimation, significantly reducing computational overhead without sacrificing performance. The Class Ensemble method was evaluated across various tasks, including classification (MNIST, CIFAR-10), semantic segmentation (U-Net on CamVid and Pascal VOC), and regression (UCI Housing dataset), and was benchmarked against traditional methods. Experimental results indicate that the Class Ensemble technique achieves competitive accuracy while offering superior calibration, robustness under noisy conditions, and efficiency in terms of memory and energy consumption. These findings suggest that the Class Ensemble method is a viable solution for uncertainty estimation in resource-limited settings, facilitating its deployment in real-time applications such as edge computing and autonomous systems.