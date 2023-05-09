# X-AID: Explanation based adversarial detection using feature attribution methods 

This folder consists of files for evaluating the unsupervised adversarial detectors. 
- MagNet: Consists of files for evaluating TPR, test FPR and AUC score of MagNet on test set. We need to first collect magnet reconstruction scores for test set the same way as we did for training set. Once we have the scores, we compare against the thresholds. 
- Other detectors: Consists of notebooks for evaluating TPR, test FPR and AUC score of feature squeeze and our detectors. We need to first collect various scores for each detectors using test set the same way as we did for training set. Once we have the scores, we compare against the thresholds. 