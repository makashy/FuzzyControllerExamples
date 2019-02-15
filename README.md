# FuzzyControllerExamples
A collection of fuzzy logic controllers implemented in ptyhon

# Fuzzy gain scheduling of PID controllers
An implementation of a paper [1] by Zhen-Yu Zhao.
### Simulation Results:
![Simulation Results](https://github.com/M-A-Kashi/FuzzyControllerExamples/blob/master/image/Fuzzy%20gain%20scheduling%20of%20PID%20controllers.png "Fuzzy gain scheduling of PID controller")

# Inverted pendulum on a cart
Simulation of controlling an inverted pendulum on a cart
![pendulum on a cart](https://github.com/M-A-Kashi/FuzzyControllerExamples/blob/master/image/pendulum%20on%20a%20cart.png "Inverted pendulum on a cart")
### Simulation Results:
![Simulation Results](https://github.com/M-A-Kashi/FuzzyControllerExamples/blob/master/image/Inverted%20pendulum%20on%20a%20cart.png "Inverted pendulum on a cart")

# Fuzzy Logic Control of a Quadrotor
    initional conditions: 
        x = 0
        y = 0
        z = 0
        Φ = 0.2
        Θ = 0.2
        Ψ = 0.2
        xd = 0
        yd = 0
        zd = 0
        Φd = 0
        Θd = 0
        Ψd = 0
        
    setpoints:
        setpoint_x=-2
        setpoint_y=3
        setpoint_z=8
        setpoint_Φ = 0
        setpoint_Θ = 0
        setpoint_Ψ = 1
        
    disturbance:
        Dx=0.1  -> drag force in x direction equivalent to a wind at 3 m / s
### Simulation Results:
![Simulation Results](https://github.com/M-A-Kashi/FuzzyControllerExamples/blob/master/image/Fuzzy%20Logic%20Control%20of%20a%20Quadrotor.png "Fuzzy Logic Control of a Quadrotor")



[1] Zhen-Yu Zhao, M. Tomizuka and S. Isaka, "Fuzzy gain scheduling of PID controllers," in IEEE Transactions on Systems, Man, and Cybernetics, vol. 23, no. 5, pp. 1392-1398, Sept.-Oct. 1993.
