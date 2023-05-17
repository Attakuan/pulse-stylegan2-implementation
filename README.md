# pulse-stylegan2-implementation
 Unofficial StyleGAN2 implementation for PULSE: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models. 
 
 The code is from the original repository: https://github.com/adamian98/pulse 
 
 Paper link: https://arxiv.org/pdf/2003.03808.pdf

 The link to the StyleGAN2 generator weights: https://drive.google.com/file/d/1wtNy8XyvRzwX-5eqnq82hhwyvtXUIoz4/view?usp=share_link
 
 
 ### Prereqs
 Setting up a local environment for StyleGAN2 can be problematic. Thus, I recommed cheking this [link](https://youtu.be/BCde68k6KXg).
 The code has been tested on Windows. However, original code wasn't originally implemented on Windows. Thus, for setting up, I also recommend checking this [link](https://youtu.be/sRu5j-mzOy0).

 For the full set of required Python packages, create a Conda environment from the provided YAML, e.g.

```
conda create -f pulse.yml 
```
or (Anaconda on Windows):
```
conda env create -n pulse -f pulse.yml
conda activate pulse
```
