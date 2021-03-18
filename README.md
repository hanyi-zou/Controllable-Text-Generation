# Controllable-Generation

![](https://img.shields.io/badge/Status-building-brightgreen)

## VAE
1. **Adversarially Regularized Autoencoders** *Jake Zhao, Yoon Kim, Kelly Zhang, Alexander M. Rush, Yann LeCun* `ICML18` [[PDF]](https://arxiv.org/pdf/1706.04223v3.pdf) [[code]](https://github.com/jakezhaojb/ARAE) ![](https://img.shields.io/badge/VAE-Adversarial-red) <details> <summary><mark>model</mark></summary> <img src="https://raw.githubusercontent.com/HappyGu0524/pic/master/img/20210318194000.png?token=AF2CKRBMW2CMCS3QTJPTSADAKM6F2" width="60%" title="Replace KL divergence with adversarial classifier" align="middle" /> </details> <details> <summary><mark>algorithm</mark></summary> <img src="https://raw.githubusercontent.com/HappyGu0524/pic/master/img/20210318194045.png?token=AF2CKRFFJB54EH27DPX5CHDAKM6H4" width="60%" align="middle" /> </details>
## VAE based
1. **T-CVAE: Transformer-Based Conditioned Variational Autoencoder for Story Completion** *Tianming Wang, Xiaojun Wan* `IJCAI19` [[PDF]](https://www.ijcai.org/proceedings/2019/0727.pdf) [[code]](https://github.com/sodawater/T-CVAE) ![](https://img.shields.io/badge/ROCStories-Story%20Infilling-orange)<details> <summary><mark>abstract</mark></summary> Story completion is a very challenging task of generating the missing plot for an incomplete story, which requires not only understanding but also inference of the given contextual clues. In this paper, we present a novel conditional variational autoencoder based on Transformer for missing plot generation. Our model uses shared attention layers for encoder and decoder, which make the most of the contextual clues, and a latent variable for learning the distribution of coherent story plots. Through drawing samples from the learned distribution, diverse reasonable plots can be generated. Both automatic and manual evaluations show that our model generates better story plots than stateof-the-art models in terms of readability, diversity and coherence.</details> <details> <summary><mark>model</mark></summary> <img src="https://raw.githubusercontent.com/HappyGu0524/pic/master/img/20210318194427.png?token=AF2CKRAGGOPBZ234T2YOVELAKM6WA" width="60%" align="middle" /> </details>
2. **Transformer-based Conditional Variational Autoencoder for Controllable Story Generation** *Le Fang, Tao Zeng, Chaochun Liu, Liefeng Bo, Wen Dong, Changyou Chen* `arXiv` [[PDF]](https://arxiv.org/pdf/2101.00828v1.pdf) [[code]](https://github.com/fangleai/TransformerCVAE) ![](https://img.shields.io/badge/WritingPrompts-Story%20Generation-orange)<details> <summary><mark>abstract</mark></summary> We investigate large-scale latent variable models (LVMs) for neural story generation—an under-explored application for open-domain long text—with objectives in two threads: generation effectiveness and controllability. LVMs, especially the variational autoencoder (VAE), have achieved both effective and controllable generation through exploiting flexible distributional latent representations. Recently, Transformers and its variants have achieved remarkable effectiveness without explicit latent representation learning, thus lack satisfying controllability in generation. In this paper, we advocate to revive latent variable modeling, essentially the power of representation learning, in the era of Transformers to enhance controllability without hurting state-of-the-art generation effectiveness. Specifically, we integrate latent representation vectors with a Transformer-based pre-trained architecture to build conditional variational autoencoder (CVAE). Model components such as encoder, decoder and the variational posterior are all built on top of pre-trained language models—GPT2 specifically in this paper. Experiments demonstrate state-of-the-art conditional generation ability of our model, as well as its excellent representation learning capability and controllability.</details> <details> <summary><mark>model</mark></summary> <img src="https://raw.githubusercontent.com/HappyGu0524/pic/master/img/20210318194813.png?token=AF2CKRHD7EAF7CRHANRTGBDAKM7EM" width="60%" align="middle" /> </details>

