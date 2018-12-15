# Forecasting-Trajectory-of-Double-Pendulum
RNN In Physics


**Physics + Machine Learning**

The double pendulum is a complex physical system which behaves chaotically (refer to the simulation).
Forecasting of such a complex system with the help of Deep Learning Architecture gives us a glimpse of what can be achieved with the application of AI algorithms in complex problems of natural sciences. The solutions can be obtained with the help of such new tools that previously required backbreaking handcrafted traditional solutions. 

The position and trajectory of doubt pendulum are forecasted based on the factors like its initial position and lengths of the rods. RNN is trained with the initial positions and movement of the bob then used it to extrapolate the path/trajectory of the double pendulum system. Different double pendulum parameters were tested to obtain an optimal system that can achieve the desired position or that can travel through the desired path. Being able to forecast such a complex system enables us to use the same techniques in complex scientific problems. We used the same technique for the forecasting of the projectile trajectory in that Initial position of projectile particles, initial velocity, angle of the launch were fed to train the RNN.   


In the near time, these projects can be modified to predict the future of highly unstable and complex systems such as weather, stock market or health-related issues.   

# Example of Double Pendulum
![](https://upload.wikimedia.org/wikipedia/commons/6/65/Trajektorie_eines_Doppelpendels.gif)

# Result
prediction of X co-ordinate
![Alt text](results/x2.png?raw=true "X prediction")

prediction of Y co-ordinate
![Alt text](results/y2.png?raw=true "Y prediction")


The RNN Network was trained on : Workstation Xeon Processor , 16GB GPU, Ubuntu 

Training sample: 10 million, each batch contains 10K sample

