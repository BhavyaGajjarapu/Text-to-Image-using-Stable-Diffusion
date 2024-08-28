# Text-to-Image-using-Stable-Diffusion
Let's convert given text to image...!!
Understanding diffusion models
Diffusion models have beaten GANs in image generation

2 primary components

UNet model: takes a random noise to generate the noise residual
Scheduler: uses the noise residual to generate a less noisy image
Pipelines such as Stable diffusion, use additional component (tokenizers) to convert the prompt to embeddings
