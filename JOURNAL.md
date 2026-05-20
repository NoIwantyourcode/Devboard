**Total Time: 13.5 hours**

# Completed Schematics - 4 hours
I completed the schematics for the devboard, This is very simple devboard however I do plan to add a bunch of features later on such as an IMU (most likely the MPU-6500) and an Magnetometer as well, I may also try to the robot shoot nerf darts out of its back later on so that will be something I might have to add additional hardware for

Heres a picture of the devboard schematic:
<img width="1991" height="1311" alt="Screenshot 2026-05-18 102844" src="https://github.com/user-attachments/assets/b85fa2ce-36cd-46fc-8095-35812270e8a5" />

# Completed routing - 5.5 hours
I completed the routing, What I ended up with is a 4 layer board with components on both sides, The reason for having components on both sides is space, by optimizing the space I can reduce the power draw of the robot and speed up reaction time of the devboard, even if it maybe marginal! 
This is why it took 5 hours as I had to do multiple iterations with each iteration getting smaller

heres a picture of the 1st V 2nd iteration:

<img width="606" height="1422" alt="Screenshot 2026-05-18 102831" src="https://github.com/user-attachments/assets/b749d444-bb92-4731-9107-35279c8c27a0" />
<img width="708" height="992" alt="Screenshot 2026-05-18 213241" src="https://github.com/user-attachments/assets/b7036fff-cf00-4a8c-be47-bab5e6c6f804" />


# Updated Schematics and PCB - 2.5 hours
I updated the schematics to include an IMU which will be used to help balance the robot on the 2 wheels it works by!
I also updated the PCB to be routed with the new IMU and made it so that it now has a silkscreen!

heres a picture of the new board

![alt text](image.png)
![alt text](<Screenshot 2026-05-20 160039.png>)

# I rerouted the PCB and removed the IMU - 1.5 hours

I removed the IMU as I couldn't figure out how to power it, I also realised that having 4 10-pin headers to make 40 pins would be inefficient and instead decided to use 2 20-pin headers to make it easier to route and work on later, I also simplified the board to go from a 4-layer PCB to 2-layer PCB

here is a picture of the board now:

<img width="942" height="1186" alt="Screenshot 2026-05-20 193705" src="https://github.com/user-attachments/assets/71bf2612-c55a-4bc0-b8da-22266c8d5be7" />
