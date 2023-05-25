# Stable Diffusion misc code
Miscellaneous code for Stable Diffusion stuff.

### Textual Inversion Colab Notebook
Changs to the original:
- Allow custom captioning
- Zip file of all embeddings (and a handy download button)
- Little QoL things like custom embed filenames etc

Future modifications to allow for multiple learning rates (if possible)

This version does not automatically re-size to 512x512 nor convert to JPEG. So train whatever size you'd like (I'd suggest 512x512).

Note that the Textual Inversion notebook is originally from Hugging Face here: https://github.com/huggingface/notebooks/blob/main/diffusers/sd_textual_inversion_training.ipynb which is licensed under Apache 2.0. and originally copyrighted by them.