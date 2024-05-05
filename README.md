# Deep-Convolutional-Q-Learning-Pac-Man

## Description

This model consists of adding to Deep Q-Learning a Convolutional Neural Network so that our AI can see images, which will be the inputs of the whole Neural Network.

Once the Neural Network, composed of first a Convolutional Neural Network and followed by a fully-connected Neural Network is build, next the model will be trained play Pac-Man, this famous game of our childhood.

## Preview
https://github.com/CoboAr/Deep-Convolutional-Q-Learning-Pac-Man/assets/144629565/9313d7c9-da2c-4049-aee9-d452b285d02b

## Requirements 
 Google Colab       
 [Gymnasium Documentation Pacman](https://gymnasium.farama.org/environments/atari/pacman/)      
 PyTorch   
 
## Environment Description

A classic arcade game. Move Pac Man around a maze collecting food and avoiding ghosts- unless you eat a Power Pellet, then you can eat the ghosts too!

## Actions
Pacman has the action space of Discrete(5) with the table below listing the meaning of each action’s meanings. To enable all 18 possible actions that can be performed on an Atari 2600, specify full_action_space=True during initialization or by passing full_action_space=True to gymnasium.make.   

<b>Value</b> &nbsp;&nbsp;   <b>Meaning</b>      
 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NOOP        
 1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;UP      
 2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RIGHT       
 3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;LEFT      
 4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DOWN    

 ## Variant Used
 <ul>
   <li>MsPacmanDeterministic-v0</li>
 </ul>

 Detereministic means that the monsters will be deterministic to make the environment less complex, and v0 is the initial version release.


Enjoy! And please do let me know if you have any comments, constructive criticism, and/or bug reports.
## Author
## Arnold Cobo


 


