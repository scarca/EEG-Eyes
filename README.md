# EEG-Eyes

Machine Learning is rapidly advancing, and a major goal throughout the community is to achieve human-machine interfacing. A major part of that, straight out of a sci-fi book, is the ability to control a computer with your mind. 

A small part of that is the ability to have a computer determine if your eyes are open or closed, with a future goal of improved eye-state tracking. 

To that extent, I found a [2013 paper](http://suendermann.com/su/pdf/aihls2013.pdf) claiming that they had acheived 97.3% classification error on 14-Channel EEG data, and that a neural network could not perform as well as their classifier. This was created in response to that. This is a simple neural network that achieves greater than 99% accuracy, while simultaneously being faster to train and test. 

Although neural networks are by-and-large black boxes, I hypothesize the success is due to my using Softplus as an activation function, which I believe better mimics brain function than a sigmoid or tanh. 

I used the following network structure: 
![Network Structure](./icon.png?raw=true "Network Structure") 
