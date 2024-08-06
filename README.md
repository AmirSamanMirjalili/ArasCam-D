# ArasCam-D
This master's thesis focuses on designing, building, and controlling a specific type of cable-driven parallel robot called an "easy-to-install underconstrained cable robot." Here are the key points of the work:

**1. Easy Installation:**

* Traditional cable robots are bulky and complex to set up. This thesis aims to create a design that simplifies and speeds up the installation process.
* The proposed robot, named Aras-Cam-2, is designed to have all its components (winches, sensors, power supply, etc.) integrated into the mobile platform.
* This allows for easy deployment: simply attach the cables to pre-defined anchor points and the robot is ready to operate.

**2. Underconstrained Design:**

* Aras-Cam-2 is designed with fewer actuators (cables) than degrees of freedom. This means it has more ways to move than it has motors to control directly.
* This underconstrained design reduces cost and complexity, but introduces control challenges.
* The thesis acknowledges the trade-off between simplicity and controllability, and focuses on developing appropriate control strategies.

**3. Trajectory Design:**

* Underconstrained robots are prone to unwanted vibrations due to uncontrolled degrees of freedom.
* A key contribution of the thesis is developing a trajectory design methodology to minimize these vibrations.
* The proposed method focuses on "rest-to-rest" trajectories, ensuring the robot starts and ends at rest, thus reducing vibrations.
* The thesis acknowledges the challenges of designing these trajectories for robots with four cables and proposes alternative approaches for future work.

**4. Mathematical Modeling and Simulation:**

* The thesis develops detailed mathematical models for the robot's kinematics (motion) and dynamics (forces).
* These models are used to simulate the robot's behavior and validate the proposed trajectory design methodology.
* The simulations demonstrate the effectiveness of the rest-to-rest trajectory design in reducing vibrations, particularly for a three-cable version of the robot.

**5. Future Work:**

* The thesis acknowledges the limitations of the current trajectory design for the four-cable robot and suggests potential solutions for future investigation.
* Two promising avenues are:
    * **Variational Integrators:** This method incorporates system constraints directly into the trajectory design, potentially improving controllability.
    * **Dynamic Factor Graphs:** This optimization-based technique offers a flexible and efficient way to design trajectories while considering various constraints and factors.


## Robot Structure (Gif is loading, please wait ... )
![Video_240309133950_Slice](https://github.com/AmirSamanMirjalili/ArasCam2_Latest/assets/57065409/612595fd-4cb1-4183-aeef-f5fafe96468e)

# My Master Thesis (in persian!)

[AmirSaman_MasterThesis.pdf](https://github.com/user-attachments/files/16510851/AmirSaman_MasterThesis.pdf)

