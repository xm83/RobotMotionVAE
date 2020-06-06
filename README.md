## Learning to Orient Towards the Focus of Attention in a Group Conversation Using Variational Auto-encoders

### Abstract
Social robots often need to operate with and around groups of people, including partaking in group conversations. During social group conversations, a robot's body orientation is a subtle and effective strategy of conveying attentiveness to the conversation and redirecting the focus of a conversation. We investigate the effectiveness of using variational auto-encoders (VAEs) to compress high-dimensional observations into low-dimensional latent state representations, from which a robot could learn motion policies in orienting towards the speaker of a conversation. We study multiple procedures for training a VAE to learn a latent representation for reconstructing the input images and predicting action values for the robot. We then evaluate the learned policy in a simulated environment and compare the VAEs' performance with that of convolutional neural networks (CNNs) that directly map high-dimensional observations to action values without learning a latent state representation. Our results suggest that the best training procedure of VAE for this task is training both the image reconstruction and action prediction together from scratch. The resulting VAE effectively learns a policy that allows the robot to orient towards the focus of attention of a group conversation by following the point of maximum social saliency (the point with maximum gaze rays' concurrence from group members). The latent space visualization also shows that the latent variables of the VAE model encode relevant information for action prediction. The best VAE model so far has comparable but not superior performance to the best CNN model. This suggests that additional constraints are needed to guide the model to learn better.
