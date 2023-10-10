# OCT_GANs
Improving the diagnosis of retinal diseases through machine learning OCT image generation.

## Partners
- [CRIStAL](https://www.cristal.univ-lille.fr/spip.php?page=rubrique&id_rubrique=1) (Lille Computer Science, Signal and Automation Research Center)
- [Temeoo](https://www.temeoo.fr/)
- [The Pitié Salpêtrière University Hospital](https://pitiesalpetriere.aphp.fr/hopital-universitaire-pitie-salpetriere/), Paris

## Objective
***The main objective of this project is to develop and evaluate an AI method to 
generate synthetic retinal OCT images from existing data. This will overcome limitations 
related to real OCT images acquisition and contribute to advances in ophthalmology research.***

The specific objectives are as follows:
- Design and implement a deep learning model capable of generating
high quality synthetic retinal OCT images.
- Collect and preprocess an existing retinal OCT dataset, ensuring
that it is representative of different retinal conditions.
- Train the AI model to generate synthetic OCT images using the set
preprocessed data.
- Evaluate the performance of the model by comparing the generated synthetic images
to real OCT images from patients.

This project will help to overcome the lack of real retinal OCT images by providing a
powerful tool for generating high-quality synthetic images, therefore helping make
progress in the field of retinopathy and medical imaging.

## Method

### 1st method : GANs
- Original GAN
- DCGAN
- ProGAN
#### Results :
Examples of generated images at a definition of 256 by 256 pixels :

![example 1](/generated_images/v11/img_0.png)
![example 2](/generated_images/v11/img_6.png)
![example 3](/generated_images/v11/img_9.png)
![example 4](/generated_images/v11/img_10.png)
![example 5](/generated_images/v11/img_11.png)
![example 6](/generated_images/v11/img_14.png)

Examples of real images :

![example real](oct_drusen_sample.png)
