# Image-Completion
This is code for Globally and Locally Consistent Image Completion
Convert this code to Keras. Keep a message when you are done converting some part of the code into Keras

# Just in-case if you don't know how to contribute to other's Repo
Check out this video : https://www.youtube.com/watch?v=yr6IzOGoMsQ

These lines are taken from tadax's repo:
## " This implementation uses 128x128 images as training data unlike paper. So the both discriminators have 1 conv layer fewer; that is, the local and global discriminator have 4 and 5 conv layers, respectively.

## I trained the GLCIC model using 5,434 face images collected from the Internet. The paper says the training should be split into three phases, but I skipped the second step. The completion network is trained with the MSE loss for 100 interatinos; then both the completion network and discriminator are trained to reach the total of 400 iterations. The entire training procedure takes roughly 16 hours on a single machine equipped with a GTX 1070. "
