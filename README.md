# Kuka KR C4-commissioning at Østfold University College
Commissioning of Kuka KR C4-Controller with Beckhoff PLC and FSoE. The project also contains basic communication with Robotiq FT300 sensor from PLC, and sending data to KR C4. The manipulator we use are the KR 3 R540 Agilus, but it should be similar for other manipulators. 

This documentation is written and shared on behalf of Østfold University College, Faculty of information technology. The school are not liable for any damage made to equipment and/or injuries to persons or animals when information from this page is used. 

Important: For this to work, you must have the EL6695-1001 Kuka version of the Beckhoff Ethercat bridge integrated into the KRC 4. 


File descriptions:
                  Kuka_robot_project_twinsafe_modbus.sln is the TwinCAT/TwinSAFE project file. It also contains a small PLC-program that                     communicates with a robotiq FT300 sensor over Modbus RTU. 
                  
                  RobotlabConfigKuka.wvs is the config file that is used to configure the robot with IO and FSoE. 
                  
                  
