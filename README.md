[//]: # (Image References)

[image1]: ./celebfaces.png "Sample Faces"

## Project Overview

Generative adversarial networks (GANs) consist of two distinct neural nets that are pitted against each other, the results of which are realistic-looking images.  The two networks are respectively called the generator and the discriminator.  

The generator create fake images by trying to mimic real images contained in a seperate training dataset.  These fake images from the generator are passed along with real images from the training dataset to a network called the discriminator.  The discriminator's goal is to correctly distinguish which images are real and which are fake from the generator.  The generator, in turn, is attempting to learn and improve itself so that its generated fake images look more and more realisitic to fool the discriminator.  

One great analogy comes from an article on skymind.ai.  The page describes the generator as a money counterfeiter and the discriminator as a police officer.  The police officer is teaching him/herself how to correctly identify counterfeit notes.  As the police officer gets better at his/her job, the counterfeiter is also learning how to make better counterfeits.  This back-and-forth competition results in more and more realistic looking counterfeit notes.

GANS are a recent development, but the potential for applications is very interesting.  Some applications uncovered thus far include:

-Generating images from descriptions provided in text (a witness describing a suspect at a crime scene for example)

-Using generators to sample candidates for drugs targeting a particular disease to existing drugs from a database

-Generating realistic images from rough sketches

-Image translations where images in one domain can be turned into images in another domain (architecture blueprints being turned into images of finished buildings)

-Creating training datasets or environments for other deep learning applications

![Sample Faces][image1]


Two sample datasets will were used for this GANs project.  The first dataset is MNIST which contains images of handwritten digits.  The second dataset is the CelebFaces Attributes Dataset (CelebA) which contains over 200K celebrity images with annotations.  For more on the CelebFaces dataset, see the link below:

http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

### Instructions

Please proceed to the jupyter notebook `dlnd_face_generation.ipynb` located in this same repository.  I have thoroughly documented this notebook with a step-by-step implementation.

Please reach out to me at stephen.jacquemin@gmail.com if you have any questions.

