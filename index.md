## Education

2019.09 - 2021.05 Master of Science in Mechanical Engineering(Robotics Tracks), Columbia University 

2015.09 - 2019.07 Bachelor of Science in Marine Engineerinng, Huazhong University of Science and Technology

## Publication
Boxi Xia, Zhicheng Song†, Jiaming Fu†, Hongbo Zhu†, Yibo Jiang, Hod Lipson, “A Legged Soft Robot Platform for Dynamic Locomotion”, ICRA, 2021. († These authors contributed equally to this work.)

## Research interets
Mechanical design and manufacture of bipedal/quadrupedal/wheeled/soft robot, Control and learning-based control for robot

## Research experience

### Design and Control of Wheeled-Bipedal Robot _(Ongoing)_    

Advisor: Wei Zhang  
CLEAR LAB, Southern University of Science and Technology  

Wheeled-Bipedal robot can integrate the advantage of high energy efficiency from wheeled robot and the capability of dealing with sophisticated terrains from bipedal robot. Mini-Nezha was designed and manufactured to accomplish various agile and versatile locomation task and cooperate with the robot arm on the robot. We are now still updating the hardware and software of the robot, I'll update more information once we've finished.

In this project, My contributes are list as below:  
    **Hardware**: Designed and manufactured the whole robobt and the PCB board inside it.  
    **Software**: Created the robots’ URDFs and simulated it in MuJuCo; Control the robot arm on the robot; Balance the robot based on LQR/PID controller.(_Ongoing_)

### Soft Quadrupedal Robot with Bipedal Running Function _(2020.11 - 2021.05)_

Advisor: Hod Lipson  
Creative Machicnes Lab, Columbia University

![Branching](./assets/Flexipod2.0.jpg)  
![Branching](./assets/PCB.jpg)  
<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/fAjOaO8Wtlg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>  

Based on the [Flexipod](https://boxixia.github.io/Flexipod/) we bulit, we develop it from a 4 DOF soft robot into a 12 DOF soft robot. With Flexipod2.0 we utilized reinforcement learning to make it run both in bipedal and quadrupedal. This project is still ongoing, I'll update more information once it is finished.  

In this project, My contributes are list as below:  
    **Hardware**: Designed and manufactured the whole robobt and the PCB board inside it. Designed and manufactured a simple cable-driven leg.  
    **Software**: Created the robots’ URDFs and simulated it in Pybullet to choose motor; Utilized standard reinforcement learning algorithm(DDPG, PPO) to make the robot run and stand in bipedal form; Accomplished real-time on-board camera streaming in C++.

### Soft Quadrupedal Robot Actuated by BLDC motor _(2020.02 - 2020.10)_

Advisor: Hod Lipson  
Creative Machicnes Lab, Columbia University

![Branching](./assets/terrain_run.jpg)
<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/3h0RwY_tpGc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

**Abstract**—We present an open-source untethered quadrupedal soft robot platform for dynamic locomotion (e.g., high-speed running and backflipping). The robot is mostly soft (80 vol.%) while driven by four geared servo motors. The robot’s soft body and soft legs were 3D printed with gyroid infill using a flexible material, enabling it to conform to the environment and passively stabilize during locomotion on multi-terrain environments. In addition, we simulated the robot in a real-time soft body simulation. With tuned gaits in simulation, the real robot can locomote at a speed of 0.9 m/s (2.5 body length/second), substantially faster than most untethered legged soft robots published to date. We hope this platform, along with its verified simulator, can catalyze the development of soft robotics.  

In this project, My contributes are listed as below:  
    **Hardware**: Designed and manufactured the whole robobt and the PCB board inside it. Designed a waterproof structure to allow the robot run under shallow water.  
    **Software**: Created the robots’ URDFs and simulated it in Pybullet to probe how the robot’s structure influences the agility of robot; Accomplished real-time on-board camera streaming in python.

For more information please visit [Flexipod](https://boxixia.github.io/Flexipod/)



### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ZhichengSong6/ZhichengSong6.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
