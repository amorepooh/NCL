## Selection of Test Sample to Improve CNN Test Efficiency based on Neuron Cluster

## Abstract
Deep neural networks (DNNs) are widely used in various domains, and the importance of their quality is emphasized. DNN testing faces the oracle problem, such as the manual labeling of large test datasets. Because manual labeling requires a significant amount of time and effort, it is important to select label-worthy test samples to minimize human effort and maximize advantages. This paper proposes a neuron cluster-based test sample selection method for selecting fault-inducing test samples based on neuron clusters. Selecting fault-inducing test samples and labeling only these test samples can mitigate the oracle problem and improve test efficiency. Through experiments using public datasets and ResNet models, we verify whether neuron clusters can predict the model's classification results. We also compare the proposed method with coverage-based test sample selection methods in terms of the test efficiency. The neuron clusters predict the model's classification results with an accuracy of at least 73%. Furthermore, our proposed method is at least 7.5% more efficient than the coverage-based test sample selection methods.

## Introduction


## Research Questions
### RQ1. Prediction

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/01-RQ1.png" width="810" height="231" />
  <figcaption><b>Prediction precision measurement</b><figcaption>
</figure>

### RQ2. Efficiency

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/02-RQ2.png" width="810" height="212" />
  <figcaption><b>Efficient test sample selection</b><figcaption>
</figure>

## Results
### RQ1. Prediction

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/03-RQ1-AN1.png" width="718" height="431" />
  <figcaption><b>Comparison of model classification and neuron cluster prediction</b></figcaption>
</figure>

### RQ2. Efficiency

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/04-RQ2-sel-MNIST.png" width="702" height="440" />
  <figcaption><b>Number of selected test samples of neuron clusters and coverage-based methods on the MNIST dataset</b><figcaption>
</figure>

<br/><br/>

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/05-RQ2-def-MNIST.png" width="702" height="440" />
  <figcaption><b>Number of defects of neuron clusters and coverage-based methods on the MNIST dataset</b><figcaption>
</figure>

<br/><br/>

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/06-RQ2-eff-MNIST.png" width="702" height="440" />
  <figcaption><b>Test efficiency of neuron clusters and coverage-based methods on the MNIST dataset</b></figcaption>
</figure>

<br/><br/>
<br/><br/>

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/07-RQ2-sel-Fa-MNIST.png" width="702" height="440" />
  <figcaption><b>Number of selected test samples of neuron clusters and coverage-based methods on the Fashion-MNIST dataset</b><figcaption>
</figure>

<br/><br/>

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/08-RQ2-def-Fa-MNIST.png" width="702" height="440" />
  <figcaption><b>Number of defects of neuron clusters and coverage-based methods on the Fashion-MNIST dataset</b><figcaption>
</figure>

<br/><br/>

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/09-RQ2-eff-Fa-MNIST.png" width="702" height="440" />
  <figcaption><b>Test efficiency of neuron clusters and coverage-based methods on the Fashion-MNIST dataset</b></figcaption>
</figure>

<br/><br/>
<br/><br/>

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/10-RQ2-sel-CIFAR-10png.png" width="702" height="440" />
  <figcaption><b>Number of selected test samples of neuron clusters and coverage-based methods on the CIFAR-10 dataset</b><figcaption>
</figure>

<br/><br/>

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/11-RQ2-def-CIFAR-10png.png" width="702" height="440" />
  <figcaption><b>Number of defects of neuron clusters and coverage-based methods on the CIFAR-10 dataset</b><figcaption>
</figure>

<br/><br/>

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/12-RQ2-eff-CIFAR-10.png" width="702" height="440" />
  <figcaption><b>Test efficiency of neuron clusters and coverage-based methods on the CIFAR-10 dataset</b></figcaption>
</figure>

<br/><br/>
<br/><br/>

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/13-RQ2-sel-STL-10png.png" width="702" height="440" />
  <figcaption><b>Number of selected test samples of neuron clusters and coverage-based methods on the STL-10 dataset</b><figcaption>
</figure>

<br/><br/>

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/14-RQ2-def-STL-10png.png" width="702" height="440" />
  <figcaption><b>Number of defects of neuron clusters and coverage-based methods on the STL-10 dataset</b><figcaption>
</figure>

<br/><br/>

<figure class="image">
  <img src="https://github.com/amorepooh/NCLU/blob/main/imgs/15-RQ2-eff-STL-10.png" width="702" height="440" />
  <figcaption><b>Test efficiency of neuron clusters and coverage-based methods on the STL-10 dataset</b></figcaption>
</figure>
