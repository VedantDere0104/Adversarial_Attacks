# Adversarial Transformation Networks: Learning to Generate Adversarial Examples :- 

Pytorch implementation of ATN .

## Abstract :- 

Multiple different approaches of generating adversarial examples have been proposed to attack
deep neural networks. These approaches involve
either directly computing gradients with respect
to the image pixels, or directly solving an optimization on the image pixels. In this work,
we present a fundamentally new method for generating adversarial examples that is fast to execute and provides exceptional diversity of output. We efficiently train feed-forward neural networks in a self-supervised manner to generate
adversarial examples against a target network or
set of networks. We call such a network an Adversarial Transformation Network (ATN). ATNs
are trained to generate adversarial examples that
minimally modify the classifier’s outputs given
the original input, while constraining the new
classification to match an adversarial target class.
We present methods to train ATNs and analyze
their effectiveness targeting a variety of MNIST
classifiers as well as the latest state-of-the-art ImageNet classifier Inception ResNet v2.

## Architecture :- 
![image](https://user-images.githubusercontent.com/76057253/134180549-38df054d-4241-470d-b3e9-83593297d483.png)



## Results :- 
![image](https://user-images.githubusercontent.com/76057253/134180753-eeb286ef-dc9c-4bd1-a1b0-247a22ecbfad.png)

```
@misc{baluja2017adversarial,
      title={Adversarial Transformation Networks: Learning to Generate Adversarial Examples}, 
      author={Shumeet Baluja and Ian Fischer},
      year={2017},
      eprint={1703.09387},
      archivePrefix={arXiv},
      primaryClass={cs.NE}
}
```
