# Diffusion
Implementation of a Diffusion Model (DDPM) on MNIST
The goal of this project is to implement a denoising diffusion probabilistic model (DDPM) to generate images from the MNIST dataset. The project will guide you through understanding and implementing both the forward and backward diffusion processes, training a neural network to denoise images, and evaluating the results.

Key steps of the project include:

Data Exploration: Load the MNIST dataset, visualize sample images, and investigate its structure. Document any references, code snippets, or tutorials used to support your implementation.

Forward Process: Implement a function that progressively adds noise to images. Consider the type of noise, variable sizes, and normalization. Experiment with a defined number of steps and visualize the noisy images to verify correctness.

Backward Process: Implement the reverse diffusion process, where the model learns to denoise images. Explore different design choices for the neural network architecture and training strategy.

Training: Train the denoising network using the noisy images generated in the forward process. Record observations about the training process, including successes, failures, and challenges encountered.

Image Generation: Use the trained model to generate images from noise. Evaluate the quality of generated images and reflect on the results.

Extensions (Optional): Discuss what changes would be needed to adapt the code for DDIM (Denoising Diffusion Implicit Models) or LDM (Latent Diffusion Models) instead of DDPM.

This project emphasizes understanding the diffusion model framework, implementing and experimenting with the algorithm, and critically analyzing both successes and challenges in model training and image generation.
