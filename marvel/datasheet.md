# DATASHEET REPORT WRITING 

### OBJECTIVES :

Study the datasheet of L293D motor 

Specify about the ICs used in L293D, PWM, H-bridge 

### Report on L293D Motor Driver IC

The L293D motor driver is the best and versatile IC that simplifies the control of DC motors. 

It's H-bridge configuration and PWM capability allow for precise control of motor direction and speed, making it an essential component in many electronic and robotic projects.

### MY LEARNINGS :

The IC used in the L293D motor 

What is pwm and how it is used here 

H-bridge , what is it and how it matters 

##### IC's used :

The L293D itself is an IC used to drive motors 

Contains two internal H-Bridge circuits

A microcontroller sends control signals to the L293D (generally present in the arduino uno)

##### PWM :

Speed control is done using Pulse Width Modulation.

The microcontroller produces PWM signals

PWM is applied to the Enable pin of the L293D motor driver IC

Motor speed changes based on duty cycle

##### H-BRIDGE :

An H-Bridge is a circuit that lets current flow through a motor in either direction, allowing the motor to rotate clockwise or counter-clockwise.

It is called an “H” bridge because the switching elements are arranged like the letter H
An H-Bridge is a circuit that lets current flow through a motor in either direction, allowing the motor to rotate clockwise or counter-clockwise.

It is called an “H” bridge because the switching elements are arranged like the letter H.