﻿这些文件夹放到caffe-master/examples目录下就可以了

ljftest_alphabet 	    accuracy: 95.72%;	小网络;		   		(62个字符，0~9，A~Z,a~z);
ljftest_alphabet_VggNet     accuracy: 97.64%; 	用VggNet训练			(62个字符，0~9，A~Z,a~z)
ljftest_alphabet_VggNet_BN  accuracy: 98.72%;	用VggNet+BN训练			(62个字符，0~9，A~Z,a~z)
ljftest_alphabet_ResNet     accuracy: 99.26%;	用ResNet训练			(62个字符，0~9，A~Z,a~z)	
ljftest_cifar10_VggNet      accuracy: 88.54%;	用VggNet训练			cifar10
ljftest_cifar10_VggNet_BN   accuracy: 90.00%;	用VggNet+BN训练			cifar10
ljftest_cifar10_ResNet      accuracy: 91.17%;	用ResNet训练(虚线部分卷积核变3能达到91.76%)	cifar10
ljftest_cifar10_ResNet_pool accuracy: 91.73%;	用ResNet训练(虚线部分用pool)	cifar10
ljftest_cifar10_WRN         accuracy: 92.21%;	用WRN训练			cifar10 
ljftest_cifar10_DenseNet    accuracy: 91.22%;	用DenseNet训练			cifar10
ljftest_cifar10_mobilenet   accuracy: 88.75%;	用mobilenet训练			cifar10

