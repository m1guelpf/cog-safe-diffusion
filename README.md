# Safe Latent Diffusion Cog model

[![Replicate](https://replicate.com/m1guelpf/safe-latent-diffusion/badge)](https://replicate.com/m1guelpf/safe-latent-diffusion)

This is an implementation of the [Safe Latent Diffusion](https://github.com/ml-research/safe-latent-diffusion) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights [with your Hugging Face auth token](https://huggingface.co/settings/tokens):

    cog run script/download-weights <your-hugging-face-auth-token>

Then, you can run predictions:

    cog predict -i prompt="monkey scuba diving"
