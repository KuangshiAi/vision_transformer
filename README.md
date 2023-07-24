# When Fine-tuning always Beats Training from Scratch: Strategies to Adopt in Vison Transformer Training
Author: Kuangshi Ai, Jiaying He

Email: kuai6409@uni.sydney.edu.au, jihe7032@uni.sydney.edu.au

Assignment 2 Research Track for COMP5329 (USYD 2023), Sydney, Australia

This repository gives implementation of our proposed method, and also experimental code of other models for comparison in our paper.

Please refer to ./When Fine-tuning always Beats Training from Scratch Strategies to Adopt in Vison Transformer Training.pdf

Training from scratch test code and result on tf_flower, CIFAR10, CIFAR100 and Tiny-ImageNet are listed in folders named by model, including original ViT-Ti, SL-ViT, DeiT and our proposed model. Transfering pre-trained ViT models are mainly work done by Google Research, we made some modification for training on our chosen datasets.

The implementations are basically made by tensorflow and torch, all jupyter notebook can be run directly on Colab (with support of Colab Pro).
## Disclaimers
Note: Some part of this repository was forked and modified from [google-research/vision_transformer](https://github.com/google-research/vision_transformer).

The following open source Keras projects also give insightful opinion and contribute a lot to our project:

[Image classification with Vision Transformer](https://keras.io/examples/vision/image_classification_with_vision_transformer/)

[Distilling Vision Transformers](https://keras.io/examples/vision/deit/)

[Train a Vision Transformer on small datasets](https://keras.io/examples/vision/vit_small_ds/)

[Investigating Vision Transformer representations](https://keras.io/examples/vision/probing_vits/)
