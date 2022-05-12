# Introduce
This project uses serial communication.
Therefore, in order to use this project, it is necessary to connect the gripper and the robot using a serial cable(USB2RS485).

* The Skill command can be used up to 100 times.

# Skill Command Usage
## RQ_INIT
 Basic serial communication parameters are fixed.
 - parameter : slave id
 - parameter(radio button) : device type (controller, flange)

## RQ_GRASP
 - parameter : position
 - parameter : speed
 - parameter : force
 - (option)parameter : device id, this is not slave id, only 0 or 1.
## RQ_RELEASE
 - parameter : position
 - parameter : speed
 - parameter : force
 - (option)parameter : device id, this is not slave id, only 0 or 1.
## RQ_GET_STATUS
Global variable(Global_statusReturn) registration required
 - parameter : status, enter the status name you want to read.
 - return : Global_statusReturn 


# Robotiq Wiring Schematic
<img src="./doc/Robotiq_Wiring_Schematic.png" width="50%" height="50%"/>

# Robotiq Pinout
<img src="./doc/Robotiq_Pinout.png" width="50%" height="50%"/>

# Robotiq Interface Specification
<img src="./doc/Robotiq_Interface.png" width="50%" height="50%"/>

# Doosan Cobot Pinout
<img src="./doc/Doosan_Pinout.png" width="30%" height="30%"/>
<img src="./doc/Doosan_Schematic.png" width="20%" height="20%"/>

