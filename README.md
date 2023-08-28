# StyleTransfer
Artistic Style Transfer

Summary: Image Style Transfer combines the objects of a content image with the ar7s7c style of
a reference image, resul7ng in a visually cap7va7ng composi7on. It merges brush strokes, colors,
and textures from the reference image to transform the content image into a unique ar7s7c
representa7on. This task is also known as domain adapta7on or image-to-image transla7on.
Objec1ves: Understand and implement Genera7ve Adversarial Networks to obtain image-toimage
transla7on.

Methodology: Tradi7onal GAN architectures face a limita7on in training image-to-image
transla7on tasks due to the need for paired images and their translated forms. However,
CycleGAN addresses this challenge by enabling the training of unpaired image-to-image
transla7on.
While CNNs like VGG19 can also be u7lized for Style Transfer, GANs have been shown to generate
more photorealis7c images, making them preferable for this task.
Hence, we will use different GAN architectures to achieve image-to-image transla7on.

Evalua1on: Evalua7on would be based on following factors:
1. Visual Inspec7on.
2. Content Preserva7on.
3. Style Consistency.
4. Perceptual metrics such as the Structural Similarity Index (SSIM) or the Perceptual
Similarity Index (PSNR).

Dataset: We will be using below men7oned datasets.
1. hXps://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-7me?select=images
2. hXps://www.kaggle.com/c/gan-ge]ng-started/data
3. 
References:
1. hXps://www.cvfounda
7on.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_C
VPR_2016_paper.pdf
2. hXps://www.v7labs.com/blog/neural-style-transfer
3. hXps://github.com/junyanz/CycleGAN
