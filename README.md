# Mushrooms classifier
For this project, I have built a convolutional neural network to classify mushroom species from the [Common genus's images Kaggle dataset](https://www.kaggle.com/maysee/mushrooms-classification-common-genuss-images). The network is based on a pretained [ResNet50](https://www.mathworks.com/help/deeplearning/ref/resnet50.html) network, finetuned with [fast.ai v2](https://www.fast.ai/2020/08/21/fastai2-launch/).

This project includes:
1. EDA of the initial Kaggle dataset
2. Oulier analysis
3. Image preprocessing
4. Building and finetuning a pretrained ResNet50 convolutional neural network
5. Model evaluation using confusion matrices and classification reports

### Technology
* [Python](https://www.python.org/) - The programming language for of this project
* [fast.ai v2](https://www.fast.ai/2020/08/21/fastai2-launch/) - A deep learning library, 
* [Scikit-learn](https://scikit-learn.org/stable/) - Model evaluation,
* [Pillow](https://python-pillow.org/) - Image processing,
* [Seaborn](https://seaborn.pydata.org/) and [Matplotlib](https://matplotlib.org/) - Data visualization, 
