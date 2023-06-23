# FastFinetuningUsingVITS
Fast Finetuning for Voice Cloning using VITS

VITS (Conditional Variational Autoencoder with Adversarial Learning for End-to-End Text-to-Speech ) is an End-to-End (encoder -> vocoder together) TTS model that takes advantage of SOTA DL techniques like GANs, VAE, Normalizing Flows. It does not require external alignment annotations and learns the text-to-audio alignment using MAS, as explained in the paper. The model architecture is a combination of GlowTTS encoder and HiFiGAN vocoder. It is a feed-forward model with x67.12 real-time factor on a GPU.<br/>
5 Chinese voices were finetuned successfully using VITS
