# Iterative Least-Likely Class Method :- 
ILLCM attack (Target FGSM) on LeNet Model on MNIST Dataset .

The authors of BIM also proposed a targeted variant of the attack called the Iterative Least-Likely Class
Method (ILLCM), where the goal is to generate an adversarial example which is misclassified as a specific
target class t.


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


## Result :- 



![2021-09-18 (3)](https://user-images.githubusercontent.com/76057253/133895418-b87da346-f474-482a-89ea-b6ea1beee72e.png)


Result when target is set to 2 .

```
@misc{kurakin2017adversarial,
      title={Adversarial examples in the physical world}, 
      author={Alexey Kurakin and Ian Goodfellow and Samy Bengio},
      year={2017},
      eprint={1607.02533},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
