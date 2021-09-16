# Adversarial Machine Learning at Scale :- 

Iterative Adversarial Attack on LeNet Model with MNIST Dataset . This is the extension of FGSM with iterative mode . We are iteratively updating image to generative adversarial image .

## LeNet Architectue :- 
![image](https://user-images.githubusercontent.com/76057253/133642690-2982d6c7-c8e2-44c7-b758-cb49c6fde4bd.png)

## Abstract :- 
Most existing machine learning classifiers are highly vulnerable to adversarial
examples. An adversarial example is a sample of input data which has been modified very slightly in a way that is intended to cause a machine learning classifier
to misclassify it. In many cases, these modifications can be so subtle that a human
observer does not even notice the modification at all, yet the classifier still makes
a mistake. Adversarial examples pose security concerns because they could be
used to perform an attack on machine learning systems, even if the adversary has
no access to the underlying model. Up to now, all previous work has assumed a
threat model in which the adversary can feed data directly into the machine learning classifier. This is not always the case for systems operating in the physical
world, for example those which are using signals from cameras and other sensors
as input. This paper shows that even in such physical world scenarios, machine
learning systems are vulnerable to adversarial examples. We demonstrate this by
feeding adversarial images obtained from a cell-phone camera to an ImageNet Inception classifier and measuring the classification accuracy of the system. We find
that a large fraction of adversarial examples are classified incorrectly even when
perceived through the camera.



## Formulas :- 

X_adv_0 = X

X_adv_N+1 = X_adv_N + alpha * sign( ∇xJ(XadvN , ytru))

Thus we are iteratively updating the image .

```
@misc{kurakin2017adversarial,
      title={Adversarial Machine Learning at Scale}, 
      author={Alexey Kurakin and Ian Goodfellow and Samy Bengio},
      year={2017},
      eprint={1611.01236},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
