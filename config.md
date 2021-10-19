passwd: ratbot2021

python package:
	1. anaconda:Anaconda3-2021.05-Linux-x86_64.sh
	2. anaconda path: /usr/local/anaconda3
	
graphic driver & cuda release:
	1. graphic driver version: 470.63.01
	2. CUDA version 11.4 update2
	3. Graphic device: Nvidia GeForce 3090
	4. cuDNN v8.2.4 (September 2nd, 2021), for CUDA 11.4, cuDNN Library for Linux(x86_64)
	
ROS NOTES:
	1. ROS_DISTRO: noetic
	2. python version: 3
	3. python path:
	4. conda activate rosenv
	5. please replace ros default python with anaconda python3 executable(e.g. /home/${USER}/.conda/envs/rosenv/bin/python3) in file: /opt/ros/${ROS_DISTRO}/_setup_util.py 1st line:
		#!/usr/bin/python3 ===> #!/home/${USER}/.conda/envs/rosenv/bin/python3
	
Qt:
	1. version:5.12.11
	2. qmake path: /usr/bin/qmake
