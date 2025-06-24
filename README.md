# HandBag Design using GAN


Designed a GAN model to generate unique handbag images by training on real data, enhancing creativity in fashion design.

## Background

The fashion industry is driven by innovation, uniqueness, and consumer preference. As trends evolve rapidly, there's a growing need for automated systems that can generate creative and novel designs. Traditional design processes are often time-consuming and rely heavily on human input. Recent advancements in deep learning, particularly Generative Adversarial Networks (GANs), have opened new possibilities in generative design tasks.

GANs, introduced by Ian Goodfellow in 2014, consist of two neural networks—the generator and the discriminator—that compete in an adversarial setting. The generator aims to produce data that mimics real samples, while the discriminator attempts to distinguish real from fake inputs. Through this competition, the generator improves its output, producing increasingly realistic and high-quality data.

In this project, GANs are applied to generate new handbag designs. By learning from a dataset of existing handbag images, the model produces unique outputs that maintain the structure and style of real fashion items—demonstrating the power of AI in creative fields.


## Dataset
The dataset for training set of HandBag images can be obtained from

https://www.kaggle.com/datasets/bashturtle/shirtshandbags

# Overview

* This project focuses on bringing uniqueness to handbag design using Generative Adversarial Networks (GANs), a technology well-suited for the fashion industry where creativity and originality are essential.
* The model comprises two networks: a generator that creates new handbag images and a discriminator that differentiates between real and generated images.
* Both networks are trained simultaneously in an adversarial process, improving the generator’s ability to produce realistic and unique outputs over time.
* A dataset of 740 handbag images from Kaggle was used to train the model, with training performed using Python 3.7 on Google Colab.
* The generator learns by producing fake images, which are then refined through feedback from the discriminator.
* The model was trained over 50 epochs with a learning rate of 0.0003.
* The project successfully generated handbag designs that were both realistic and distinct, demonstrating how GANs can innovate product design and be extended to other domains beyond fashion.


# Results and discussion

* During training, the GAN-generated images were evaluated at various epochs—specifically the 1st, 10th, 20th, 30th, 40th, 45th, and 50th.
* A noticeable improvement in image clarity and quality was observed as training progressed.
* Initially, the outputs were noisy and lacked definition, but by the 50th epoch, the images exhibited reduced noise and better structure.
* After experimenting with different learning rates, a value of 0.003 was found to be optimal for generating clearer images.
* The results highlighted the importance of carefully selecting hyperparameters such as the learning rate and number of epochs.
* Too many epochs can lead to overfitting, while too few can cause underfitting and excessive noise. In GANs especially, the choice of these parameters significantly affects the quality and realism of the generated outputs.
* Overall, the results demonstrated progressive learning and the ability of GANs to produce realistic handbag designs.
