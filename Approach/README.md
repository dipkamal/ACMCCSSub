# X-AID: Explanation based adversarial detection using feature attribution methods 

We provide two notebooks for collecting various statistical and non-statistical measures of benign and adversarial images for MNIST, CIFAR and ImageNet. Each notebook consists of implementation of following approaches: 
- Approach 1: Input squeeze
- Approach 2: Sensitivity to noise 
- Approach 3: Statistical measures

Our detectors are combination of these approaches. We collect different metrics based on these approaches for both bengin and adversarial images. We only use measures from benign images to learn thresholds for our adversarial detectors. We use adversarial measures for visualization purposes. 