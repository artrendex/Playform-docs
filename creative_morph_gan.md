---
layout: page
title: "Creative Morph"
description: "Morph between images using own trained GAN - uncanny aesthetics"
permalink: /creative_morph_gan/

---
# Creative Morph GAN

## What is Creative Morph GAN ?
This process generates a sequence of images that initially resemble one set of input images and then gradually converge toward a second set. The images in-between are exploratory mixtures of the two.


<iframe width="679" height="382" src="https://www.youtube.com/embed/f9ETtW4ho0s" title="Tutorial - Creative Morph - Train your AI to morph images from one set to another" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## What inputs are needed and what results will I get?

The Creative Morph process requires two sets of input images, called Inspiration and Influences, with 30+ images in each. As the model learns how to translate from one image set to the other, it attempts to preserve the contours and shapes present in the Inspiration images, while taking cues from the colors within the Influence images.
Each iteration of training generates one output image per Inspiration image provided. For instance, 200 Inspiration images trained for 50 snapshots will create 10,000 result images (200 per iteration).
Currently, this model outputs 512 x 512 px results that can be upscaled.

## How do I train a Creative Morph model?

From the Home dashboard click "Create a Project" and choose "Creative Morph" process

The Creative Morph model requires at least two collections of images: one in Inspiration and another in Influences. You can also upload multiple collections for each input set.

You will need to Upload Images to make a new collection or choose a Recently Used collection. Only selected images will be used in the model.
You can start training by clicking the yellow button on the upper right corner. The recommended training time is 1 hour and 30 minutes, which roughly translates to 50 snapshots.

Once your model has begun training, you can access your results within just a few minutes. These first images will start off looking like the Inspiration images and slowly converge towards the Influence images.


## Related Processes
- [Freeform GAN: Train your own GAN AI Model based on your own images](./freeform_gan.md)
- [Freeform Diffusion: get clear figures and patterns from fewer images](./prompt-free-generation.md)



## FAQs

### Why can I only download images at 512x512px?
Traditionally, it takes exponentially longer to train a model to create larger results. Because of this, we have optimized the process to create 512px images for you to be able to experiment more quickly. You can also upscale your images in the single image view, with more sophisticated AI upscale methods available for Plus members.

### What kind of results do I get when the Inspiration and the Influences inputs sets are the same?

This will not challenge the Creative Morph process, so you will end up getting the exact same images you inputted. Since you do not want to be spending resources to get no results, we will make sure to alert you if you have redundant collections.

### Why the results seems uncanny ?
The creative morph process is based on traditional GAN (Generative Adversarial Network) a model widely used in classical AI Art and is appreciated because of the uncanny aethetics it gives. If you are looking for more clear figures, try the [freeform diffusion process](./prompt-free-generation.md)

[Learn more about different ways to train your own AI for AI art](https://playform.io/train)