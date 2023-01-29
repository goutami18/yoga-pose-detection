# yoga-pose-detection
The files contain pose detection using vgg16, vgg19, ResNet18, ResNet50 and movenet.

POSSIBLE APPROACHS AND DETAILS:
-The top-down approach obtains keypoints by using a module to detect human subjects to which a pose estimator can be applied. The top-down approach comprises of three components – a human candidate detector, a single person pose estimator and a human pose tracker. 
-The bottom-up approach involves detection of human keypoints from potential subjects and organizing them into human limbs using several data association mechanisms. It provides a very good compensation between cost and accuracy. 
-Generative procedures provide a technique to predict the features from a given pose hypothesis. Generative based approaches offer easy generalization due to less constraint of a training pose dataset.
-Discriminative methods start with the evidence of the image and learn a technique to model the relationship between the human poses and evidence on the basis of training data. Model testing in discriminative methods is a lot faster as opposed to generative methods
-Keypoint detection methods - Openpose, Posenet, pifpaf, High-Resolution Net (HRNet), DeepCut, Deep pose, Dense Pose, Movenet
-Pose classification using Deep Learning – MLP, RNN, CNN
