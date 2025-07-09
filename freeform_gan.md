---
layout: page
title: "Freeform GAN"
description: "Train your own GAN on your images to get classical AI Image uncanny aesthetics"
permalink: /creative_morph_gan/


---
# Freeform GAN

## What is Freeform GAN

The Freeform process train a GAN model (Generative Adversarial Network) based on your own images. While and After the model is trained, the model generates images that are amalgamations of the input collection. Through training, these resulting images resolve more clearly over time. 

<iframe width="679" height="382" src="https://www.youtube.com/embed/V5Tx0bbGOEY" title="Tutorial - Freeform From Playform - use AI to create your own images" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## What inputs are needed? What will I get from this process?

One collection of 30+ images is needed for the model as input, but a larger number, higher resolution, and more contextually similar images will create a better model.

Every snapshot during training will generate 50 new Freeform images. These images come at 1024 x 1024px resolution. 

The training process in general is very efficient, usually can be done in 1 or 2 hours. 

## How do I set up the model?

From the Home dashboard click **"Create a Project"** and choose "Freeform".

Freeform models require one input set of images: Inspiration.
You will need to Upload Images to make a new collection or choose a Recently Used collection, or add from Public Collections.
Only selected images will be used in the model.

You can **Start Training** your model by clicking the yellow button on the upper right corner. 

The recommended training time is is 2.5 hours as a start, which roughly translates 50 snapshots with 50 images each, i.e. 2,500 resulting images.  

Once your model has begun training, you can access your Results within just a few minutes. The first images begin relatively noisy and resolve more clearly with more training.

**Continue Training**: Depending on your input images, some project might benefit from more iterations. You can click the orange Continue Training button in the top right to create more snapshots.  

## After Training: Mixing and Morphing Videos

Once the model is trained, you can generate infinite number of images. You can mix between images to get precise results. You can also create morph videos between images. [Learn about Mix and Morph videos](./freeform_mix.md)

## Related Processes
- [Freeform Diffusion: get clear figures and patterns from fewer images](./prompt-free-generation.md)
- [Creative Morph GAN: How to generate images morphing between two sets](./creative_morph_gan.md)

## FAQs
### How many images should I input?
The more the better! The minimum is 30, but you can upload as many as 5000. The images should be (ideally) at 1024px for Freeform. We accept PNGs and JPGs. Though uploading lower resolution images for your specific model is possible, results will likely exhibit a degraded quality.

### What kinds of inputs gives the best results?
We find that a well-curated, large image set works really well. The more consistent the images, the better the results. Notice, as a GAN model, by default the results will have uncanny aethetics of classical AI art, unlike Diffusion-based model. If you are interested in clear figures and pattern, [check out Freeform Diffusion](./prompt-free-generation.md)

### How many results do you get?
You will get 50 resulting images per snapshot, regardless of the amount of images you inputted during training. For the Freeform model, you can also generate more resulting images using Mix, which uses the trained model from your most recent snapshot.

### Many of my results look the same. Why?
This is called Mode Collapse, and it's a well-documented phenomenon that Generative Adversarial Networks (GANs) exhibit. Though it's a part of the mathematical properties of the AI model.  This is more likely to happen if there are not enough variations in the inspiration images or if the model has been trained for very long time. 


### What can I expect if I "continue training" on a Freeform project? How to tell if training is done?
The results should look more and more similar to your input images as you train more snapshots/iterations. However, after a few hundred snapshots, any subsequent training will have very little effect on the results and can result in the images looking largely similar. 


[Learn more about different ways to train your AI models using Playform](https://playform.io/train)