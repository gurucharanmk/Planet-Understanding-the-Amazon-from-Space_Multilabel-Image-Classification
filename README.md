
# Planet-Understanding-the-Amazon-from-Space_Multilabel-Image-Classification

  
  

### Overview

Every minute, the world loses an area of forest the size of 48 football fields. And deforestation in the Amazon Basin accounts for the largest share, contributing to reduced biodiversity, habitat loss, climate change, and other devastating effects. But better data about the location of deforestation and human encroachment on forests can help governments and local stakeholders respond more quickly and effectively.

  

For this cause [Planet](https://www.planet.com/) released dataset in [Kaggle](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/overview) on July 2013, with multilabel images.

  
  
  

### Implementation details

| Feature | Brief Explanation |
| ------ | ------ |
| Base Model Architecture | Resnet50 from [ResNet](https://arxiv.org/abs/1512.03385) family, implementation from [PyTorch](https://pytorch.org/)|
| Learning Rate Finder | [Learning rate finder](https://arxiv.org/abs/1506.01186) implementation from [FastAI](https://www.fast.ai/) |
| Learning rate and Momentum scheduler| [One cycle policy](https://arxiv.org/abs/1803.09820) implementation from [FastAI](https://www.fast.ai/) to achieve superconvergence |
| Dataset | Dataset was taken from [mirrored location](https://www.kaggle.com/nikitarom/planets-dataset) from [nik](https://www.kaggle.com/nikitarom) |

  
  

### Results

| Model | Score(on Kaggle) | Epochs |
| ------ | ------ | ------ |
| Resnet50 | 0.93095 | 16 |

  
  
  

#### Score detail

![Alt text](https://github.com/gurucharanmk/Planet-Understanding-the-Amazon-from-Space_Multilabel-Image-Classification/blob/main/images/score.png )

  

## License

This project is licensed under the [MIT License](https://github.com/gurucharanmk/Planet-Understanding-the-Amazon-from-Space_Multilabel-Image-Classification/blob/main/LICENSE)
