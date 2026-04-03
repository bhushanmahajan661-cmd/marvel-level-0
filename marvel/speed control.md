# Speed Control of DC Motor

### OBJECTIVES :
To control the speed of an h-bridge L298N motor driver using an  L298N motor module and arduino uno

### MY LEARNINGS :

I learnt how an L298N motor driver functions and what are it's various sockets and connections and that we can hook it upto 2  motors simultaneously 

The basic working principle of the H-bridge L298N motor driver and how it changes the speed based on the periodically altering volatge supply provided to it by the L298N motor driver 

The H-bridge L298N motor driver has 4 electrodes which control direction and speed based on the applied voltage it has its own specific truth tables for this process to happen and the fluctuating volatage is supplied by the L298N motor module in the high voltage mode one series of network will be connected and the motor will rotate in one direction and speed , when a lower voltage is applied the switch changes and a new network will be initiated which rotates the motor in different direction and different speed 

It has the 4 electrodes arranged in the forma of an H with a switch in middle and sides which governs the speed and direction the H-bridge L298N motor 

The aurdiono board takes care of the execution of the code instructing the L298N motor module which specifies the module to supply the right amount of voltage at set intervals 
controlling the execution of the desired output 

![alt text] (speed control.png)