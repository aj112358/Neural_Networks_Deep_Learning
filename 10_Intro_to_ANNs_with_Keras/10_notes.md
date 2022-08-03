# Ch 10 - Introduction to Artifical Neural Networks with Keras

## Chapter Objectives
1. Introduction to ANN architecture
2. Learn about multilayer perceptrons
3. How to implement ANN using the Keras API

An "artificial neural network" (ANN) is a ML model inspired by the brain's own biological neural network, and it makes up the foundation for deep learning (DL). They are ideal at tackling highly complex ML problems, some examples of which are:
- Classifying billions of images (ex: Google images)
- Speech recognition services (ex: Apple Siri)
- Recommendation for music and videos (ex: YouTube)
- Computer games involving AI (ex: DeepMind's Alpha Go)

## 10.1 - From Biological to Artifical Neurons

The concept of an ANN was first introduced in 1943 by Warren McCulloch (neurophysiologist) and Walter Pitts (mathematician). They used propositional logic to create a simplified computational model of how biological neurons might work together to perform complex computations. Since then, many other architectures have been invented.

The societal belief that intelligent machines would soon be created was let down, and so did the funding, causing the research of ANNs to be held at a standstill until in the 1980s, when new architectures were invented and better training techniques were developed. This sparked what is now called "connectionism" which describes the study of explaning intellectual abilities using ANNs. Unfortunately, by the 1990s, other ML algorithms were invented which seemed to provide better results than ANNs, and so ANN research was again put on the shelf.

Now, in the 2020s we are in yet another wave of interest in neural networks. Luckily, here are a few reasons why the author believes that this time ANNs will have a greater impact:
- There is lots of big data available to train ANNs, and ANNs frequently outperform the other usual ML techniques at these larger/more complex scales
- There is much more computing power available (Moore's Law, gaming GPUs, cloud platforms)
- The actual neural network training algorithms have improved
- Theoretical limitations of ANNs do not frequently appear in practice
- There is lots of funding for more research


### 10.1.1 - Biological Neurons

We first start our journey by looking into a biological neuron.

![biological-neuron](https://github.com/aj112358/Neural_Networks_Deep_Learning/blob/main/10_Intro_to_ANNs_with_Keras/10_images/biological_neuron.png)

Since I am already familiar with anatomy and physiology, we won't go too much in-depth regarding this image. Essentially, the neuron will produce action potentials which travel along it's dendrite and release neurotransmitters at the synapses. Once a sufficient amount of neurotransmitters have been released, the desired function will be exhibited, and the second neuron will begin to fire it's own action potential.

This quite simple mechanism works on a much grander scale, onto billions of neurons, each of which could be connected to thousands of other neurons. And thus, we can believe that highly complex computations **CAN** be performed using a collection of such simple neurons, which supports the claim for research of ANNs


### 10.1.2 - Logical Computations with Neurons





