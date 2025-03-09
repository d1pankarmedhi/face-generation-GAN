<div align="center">
<h1>Human Face Generation with GAN</h1>  
  
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Python Version](https://img.shields.io/badge/Python-3.6+-brightgreen.svg)](https://www.python.org/downloads/) [![TensorFlow Version](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://www.tensorflow.org/)

<p>Create realistic faces using Generative Adversarial Networks</p>
</div>

This repository covers what GANs are and shows how to train a GAN model to generate lifelike human faces using the CelebFaces dataset.  

## What is GAN?

Generative Adversarial Networks (GAN) is an approach of generating images. It is a combination of main components - *Generator* and *Discriminator*. 

- **Generator** takes in random noise vectors and transforms them into synthetic data, image, audio or text. There aim is to produce data which is similar to the original sample data it is trained on. 

- **Discriminator** on the other hand acts as a critic and evaluates the given data samples as original or fake. Its job is to observe and classify real data as real and generated data samples as fake. 


Through this adversarial process, the Generator learns to create increasingly realistic faces, while the Discriminator gets better at spotting fakes.

## Getting Started 

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/face-generation-GAN.git
    cd face-generation-GAN
    ```

2.  **Download the CelebA Dataset:**
    (Provide instructions or a link to download the dataset.)
3.  **Run the Notebook:**
    Open `notebooks/GAN_face_generation.ipynb` in Jupyter Notebook or Google Colab and follow the instructions.

## Sample Generation (After Just 5 Epochs!) 

<div align="center">
<img src="https://github.com/user-attachments/assets/db31db02-fc16-46e8-9e6f-85923137f2f7" width=200>
<p>Fig: Sample generation, trained for 5 epochs only</p>
</div>

**Note:** Even after just 5 epochs, you can see the beginnings of face-like structures! With more training, the results become even more impressive.
