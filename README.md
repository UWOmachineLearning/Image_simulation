# Image conversion

The objective of this project is to convert an MP2RAGE image (MR image with T1 contrast) to a FLASH image (MR image with T2 contrast). The data set we are using is open source 7T brain images:http://datadryad.org/resource/doi:10.5061/dryad.fb41s. Our current plan is to implement a CNN in tensorflow for this task.

# Progress Summary
We are beginning with a slightly easier task: The MP2RAGE acquisition has two different images (acquired with different inversion times so they have different contrast); our preliminary goal is to convert one of these images to the other.

So far we have implemented a prototype CNN in tensorflow that is TRYING to convert the image. The output looks like a blurry brain with contrast that somewhat resembles the contrast of the target output. Obviously there is a lot more work to be done

# Near future objectives
- continue to optimize the CNN architecture and hyperparameters
- learn how to implement sparsely connected layers instead of fully connected layers
- register the MPRAGE volumes with the FLASH volumes. 

# dependencies
- tensorflow
