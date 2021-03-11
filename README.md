# Communicative Learning via Instructional Gestures for Embodied Navigation Agents
by Qi Wu, Cheng-Ju Wu, Yixin Zhu, and Jungseock Joo

## Introduction
This work is inspired by the natural human-human gesture communication and intend to extend the exisiting vision-language navigation (VLN) framework by adding gestures as the communicative interface.

To achieve this, we have developed a simulation environment based on AI2-THOR, and allow the human players to interactively communicate with the navigation agent in a VR setting using gestures. We also show that in our environment, by training the agent using gestures via proximal policy optimization (PPO), the agent is not only able to improve its navigation performance but also understand the underlined meaning and intents of human gestures.

Please refer to our paper for detailed formulations.

## Setup
Our GesTHOR environment is based on [AI2-THOR](https://ai2thor.allenai.org/). We provide a Unity standalone build tested on Ubuntu 18.04 and 20.04. 

### Unity Local Build
If you want to check our C# source code or add your own implementations, please refer to this [repository](https://github.com/KevinWu57/GesTHOR_local_build).  
