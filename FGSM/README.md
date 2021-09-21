# FGSM Attack on LeNet on MNIST Dataset :- 


## Abstract :- 
Several machine learning models, including neural networks, consistently misclassify adversarial examples—inputs formed by applying small but intentionally
worst-case perturbations to examples from the dataset, such that the perturbed input results in the model outputting an incorrect answer with high confidence. Early
attempts at explaining this phenomenon focused on nonlinearity and overfitting.
We argue instead that the primary cause of neural networks’ vulnerability to adversarial perturbation is their linear nature. This explanation is supported by new
quantitative results while giving the first explanation of the most intriguing fact
about them: their generalization across architectures and training sets. Moreover,
this view yields a simple and fast method of generating adversarial examples. Using this approach to provide examples for adversarial training, we reduce the test
set error of a maxout network on the MNIST dataset.

## Framework :- 
![image](https://user-images.githubusercontent.com/76057253/134182848-b4271761-297d-4b22-a358-a08ed882a9fa.png)


## Results :- 
![image](https://user-images.githubusercontent.com/76057253/134182730-cbebd35e-9bf2-4d8a-97d3-95a99397eab3.png)


```
@misc{goodfellow2015explaining,
      title={Explaining and Harnessing Adversarial Examples}, 
      author={Ian J. Goodfellow and Jonathon Shlens and Christian Szegedy},
      year={2015},
      eprint={1412.6572},
      archivePrefix={arXiv},
      primaryClass={stat.ML}
}
```
