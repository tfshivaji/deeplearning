### Install on Tensorflow Single Node Cluster

In this section we will discuss how to Enable Tensorflow on a single node cluster

QDS provide "bootstrap" to install new libararies via the BootStrap section.

Navigate to the Clusters tab on the QDS Console
![Console](https://github.com/tfshivaji/deeplearning/blob/master/images/Screen%20Shot%202017-06-05%20at%203.13.36%20PM.png)

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

[<<return](https://github.com/tfshivaji/deeplearning) 