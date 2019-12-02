# DigitalConceptTutorial
Author: Brady Webb

This tuturial will cover the use of terminal on the Mac OS and how to connect it to an AWS account. Terminal is a very powerful tool avaiable on your mac. It has the ability to do things much faster than you would on the regular user interface. This tutorial will cover many useful things such as basic commands, what an AWS ec2 instance is, how to setup an instance, and finally how to connect to this instance.

This tutorial is for people who have never used terminal and need the understand the basics and power of terminal. The age group can be anyone who has access to a Mac computer or virtual machine. This tutorial will show you how to use termial in its basics as well as getting into your AWS instance.

## Getting Started
With getting started in termial we need to find it on our computer. If it is not on your task bar at the bottom of your
computer you can hit 'command' and 'space' button at the same time. This will bring up your spotlight search. 
You can then type in "terminal" and hit the enter key.

![Terminal image](https://i.ytimg.com/vi/zw7Nd67_aFw/maxresdefault.jpg)

## Basic Commands
Some of the most simple and usful commands we will go over in this section starting with the 'cd' command. This command allwos us to change directories. In terminal run the command: 'cd desktop'. This will start by moving us to our desktop directory.

The next command we can run is the 'ls' command. This command will display all the contents of our current directory.

There are many different commands to be used in termial more of which are listed at this resource.
[terminal help](https://www.techrepublic.com/article/16-terminal-commands-every-user-should-know/)

## Starting our AWS Instance
First navigate to [AmazonAWS](https://aws.amazon.com)
Here you will need to make an Amazon AWS account and get to the home page. When at the home page click on the 'EC2 Dashboard' link on the left then the 'running instances' button.
Here you will need to create a new instance. Many kinds of instances can be created and to create it follow this helpful artical on starting instances.
**This will have you create a key. Make sure you save the key to a folder on your desktop.**
[EC2Creation](https://docs.aws.amazon.com/efs/latest/ug/gs-step-one-create-ec2-resources.html)
This will have you create a key. Make sure you save the key to a folder in your desktop.

## Contecting to your EC2 Instance
After creating your instance click the connect button and page should pop up.
There will be an example section with text on what to connect and we need to copy this test to our clipboard.
![example](https://howtodoinjava.com/wp-content/uploads/2017/07/EC2_15.jpg)
Next we will need to go back to terminal. We will then use the command 'cd desktop' to move into our desktop directory where our key was saved. You will then paste what we copied from our ec2 instance and hit enter. It will ask you if you are sure you would like to connect and type 'y'. You should see the following page after completion.
![terminalPage](https://d2908q01vomqb2.cloudfront.net/1b6453892473a467d07372d45eb05abc2031647a/2019/06/25/Picture1-2.png)
Finally you will be connected to your new Amazon Ec2 instance and can make any necisary modifications.
