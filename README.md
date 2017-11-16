
## Deep Learning

Artificial Intelligence brings actions closer to analysis, making business processes to be Autonmous. It cuts the manual process of analysis to work directly with Actions. From drones to supply chain, flying cars to smart environments, artificial intelligence is changing every step of our lives. 

Environmental impact of reducing data center Energy Usage done by Deep Mind for Google, or making roads safer with Self Driving Cars used by NVIDIA, Google or Uber, deep learning is making everyday life better.

Cameras can now see, microphones can hear and detect, text are understood in context. Languages are understood, speech can be mimcked, art can be generated. Global communications are no longer restricted by language boundaries, Google's machine translation has got human level accuracy in last 6 months.

### Deep Learning

Deep Learning is at the center of AI. With the recent discoveries in Activation Functions, cheap compute at teraflops scale with (GPUs), AI is moving into every part of our lives.

### Tensorflow Install on QDS

Folw the [Install Guide](https://github.com/tfshivaji/deeplearning/blob/master/Install.md) to setup your cluster with Tensorflow and related libraries.

### Apache Zepplin Notebook

In this section we take a humble approach and show you how you can leverage data to use the power of DeepLearning on Hadoop using Zepplin Notebook


### A quick Intro to Deep Learning

<a href="http://www.youtube.com/watch?feature=player_embedded&v=iF8dRePlPUo&list=PLAwxTw4SYaPn_OWPFT9ulXLuQrImzHfOV" target="_blank"><img src="http://img.youtube.com/vi/iF8dRePlPUo/0.jpg" 
alt="Deep Learning by Google" width="580" height="400" border="10" /></a>

### Repository

The **aim** of these notebooks is to give you an introduction to the Tensorflow and Keras libraries. This repository is for sample code and to setup and get started on QDS with Zepplin Notebooks. 


The github repo provides details on the samples. 

```
	tensorflow - Contains code for tensorflow
	startup_scripts - These are QDS startup scripts
	
```
- Use the startup scripts to change the bootstrap that will install the needed libraries
- Start with 
```
	tensorflow/Tensorflow_Hello_World
	tensorflow/Tensorflow_Hello_World_Part2
```

Notebooks - These are Zepplin Notebooks. 

### Support or Contact
Please contact shivaji@aurius.io for the above work

### Known Issues
There is a known issue with using matplotlib on the Zepplin Notebook. The backend used by default is "TKAgg". This needs to be changed to "agg".
