# Yoga Pose Detection

Yoga, like other exercises, it is crucial to practice correctly because any incorrect posture used during a yoga session can be useless and even uncomfortable and may affect the health too negatively.
Practice and wellness are two applications of posture evaluation that have attracted many analysts in this subject.
Human pose estimation is a challenging task as the body’s appearance and joins changes dynamically due to diverse forms of clothes, arbitrary occlusion, occlusions due to the viewing angle, and background contexts.
Pose detection can be used in a variety of applications, including fitness apps, wearable devices, and research and development.

### POSSIBLE APPROACHS AND DETAILS:

-The top-down approach obtains keypoints by using a module to detect human subjects to which a pose estimator can be applied. The top-down approach comprises of three components – a human candidate detector, a single person pose estimator and a human pose tracker. 

-The bottom-up approach involves detection of human keypoints from potential subjects and organizing them into human limbs using several data association mechanisms. It provides a very good compensation between cost and accuracy. 

-Generative procedures provide a technique to predict the features from a given pose hypothesis. Generative based approaches offer easy generalization due to less constraint of a training pose dataset.

-Discriminative methods start with the evidence of the image and learn a technique to model the relationship between the human poses and evidence on the basis of training data. Model testing in discriminative methods is a lot faster as opposed to generative methods

-Keypoint detection methods - Openpose, Posenet, pifpaf, High-Resolution Net (HRNet), DeepCut, Deep pose, Dense Pose, Movenet

-Pose classification using Deep Learning – MLP, RNN, CNN

### MODELS:

Neural Network: A type of machine learning model that is composed of layers of interconnected nodes, called neurons. Neural networks are often used for tasks such as image recognition and natural language processing.

CNN: A type of neural network that is designed for image recognition and processing. It uses convolutional filters to learn spatial hierarchies of features from the input data.

Transfer Learning: Using a pre-trained model on one task as the starting point for a model on a different but related task. This can help improve the performance of the model when there is limited data available.

Pretrained Models: A pre-trained model is a machine learning model that has already been trained on a large dataset and is made available for use in other applications. Pre-trained models can help improve the performance and speed up the training process for new models.

### Pre Trained Models used:

VGG16

VGG19

Resnet18

Resnet50


### KeyPoint Detection
-A Human Pose Skeleton represents the orientation of a person in a graphical format.

-Each coordinate in the skeleton is known as a part (or a joint, or a keypoint).

-A valid connection between two parts is known as a pair (or a limb).

-Human pose estimation aims at predicting the poses of human body parts and joints in images or videos.

-Find the location of key points and use set of coordinates that can be connected to describe the pose of the person.

