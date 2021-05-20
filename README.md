# FGSM_Facial_Privacy
Fooling the facial classification network to restore privacy using Fast Gradient Sign Method  
#### The GTSB 50 faces dataset can be found <a href="http://www.anefian.com/research/face_reco.htm">here</a>  
## Fast gradient sign method(FGSM)  
The fast gradient sign method works by using the gradients of the neural network to create an adversarial example. For an input image, the method uses the gradients of the loss with respect to the input image to create a new image that maximises the loss. This new image is called the adversarial image. This can be summarised using the following expression:

                            adv_x = x + e*sign(delx J(theta,x,y))

where

adv_x : Adversarial image.  
x : Original input image.  
y : Original input label.  
e : Multiplier to ensure the perturbations are small.  
theta : Model parameters.  
J : Loss.  
### Execute the <a href="http://www.anefian.com/research/face_reco.htm">FGSMAttack_FaceRecognition.ipynb</a> for reproducing the results.  

