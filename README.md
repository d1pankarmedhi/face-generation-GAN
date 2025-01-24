# Human Face Generation with GAN


Generative Adversarial Networks (GAN) is an approach of generating images. It is a combination of main components - *Generator* and *Discriminator*. 

- **Generator** takes in random noise vectors and transforms them into synthetic data, image, audio or text. There aim is to produce data which is similar to the original sample data it is trained on. 
- **Discriminator** on the other hand acts as a critic and evaluates the given data samples as original or fake. Its job is to observe and classify real data as real and generated data samples as fake. 

Built on this principle, a traditional GAN is trained on celeb faces dataset, with a sole purpose of generating images that resembles the original data as closely as possible. 

<div style="text-align:center">
<img src="https://github.com/user-attachments/assets/db31db02-fc16-46e8-9e6f-85923137f2f7" width=200>
<p>Fig: Sample generation, trained for 5 epochs only</p>
</div>

Traditional GAN training template with MNIST test run and Celeb face generation. in [notebooks/GAN_face_generation.ipynb](/notebooks/GAN_face_generation.ipynb)





