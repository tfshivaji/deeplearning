### Install on Tensorflow Single Node Cluster

In this section we will discuss how to Enable Tensorflow on a single node cluster

QDS provide "bootstrap" to install new libararies via the BootStrap section.

Navigate to the Clusters tab on the QDS Console
<img src="/images/Screen%20Shot%202017-06-05%20at%203.13.36%20PM.png" height="100" width="100"></img>

Click on the "Edit Node Bootstrap" link
![Edit BootStrap](https://github.com/tfshivaji/deeplearning/blob/master/images/EditBootStrp01.png)

Add the following to script area:
	
	source /usr/lib/hustler/bin/qubole-bash-lib.sh
	make-python2.7-system-default
	pip install pandas
	pip install keras
	pip install numpy
	pip install SciPy
	pip install tensorflow
	pip install h5py
	pip install pyparsing
	pip install graphviz
	
As shown in the image.	
![Add pip install libraries](https://github.com/tfshivaji/deeplearning/blob/master/images/EditBootStrap02.png)

Save and **Start/Restart** the Cluster.

Watch the ***"Cluster Startup Logs"*** for any errors.

### Future work 

Tensorflow comes with [tensorboard](https://www.tensorflow.org/get_started/summaries_and_tensorboard). Tensorboard will work with tensorflow. Please work with your AWS admin to open the ports for tensorboard. Please follow the tensorflow documentation on how to run tensorboard. 

[<<return](https://github.com/tfshivaji/deeplearning) 
