<h1>3rd Party Robotics Toolboxes for MATLAB</h1>

These toolboxes are used for the Robotics course that is conducted by Dr. Cathy Ann Radix.
This course is currently conducted at the Department of Electrical and Computer Engineering, The University of the West Indies, St. Augustine, Trinidad W.I.

Please note at the point of time of writing this, the MATLAB version used for all of these toolboxes is R2022a.

The instructions for how to go about adding these toolboxes are listed below:
-----------------------------------------------------------------------------

1. Check if the official MATLAB toolboxes are installed first. We can do this by going to Apps tab and click “Get More Apps” and then “Manage Apps”.
    - Deep Learning
    - Fuzy Logic
    - Navigation
    - Reinforcement Learning
    - Robotics System
    - ROS
    - Sensor Fusion and Tracking
    - UAV
2. Ensure that Simulink is installed as well. This is required for some of the toolboxes.
3. If they are not there, re-run MATLAB installer and have them included automatically. The manual process involves adding them one-by-one which is time consuming.
4. The last four toolboxes are 3rd party and require downloads. Thankfully they are provided in this repository:
    - Mobile Robotics Simulation
    - Robotics
    - Spatial Math (Needed for Robotics)
    - Common Toolbox (Needed for Robotics)
    - ROV Design Analysis
    - KalibRot
5. Copy each of their folders straight into the toolbox folder where MATLAB is installed on your local machine.
6. Run the pathtool command in MATLAB and ensure that you select "Add folder and subfolders" for each of these project folders. You will have to do this one by one since MATLAB does not allow multiple selection in the pathtool GUI.
7. You can test if the toolboxes can be seen in any folder from MATLAB by calling the name of any of their scripts. For example, to test if the Robotics Toolbox was included correctly, we can run the rtbdemo command.
8. Finally, always read the included documentation on how to use each of these toolboxes. Each folder includes their documentation, which is really helpful.