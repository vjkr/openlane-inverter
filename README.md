<details>
<summary># openlane-inverter aborted after short success</summary>

Work completed with all documentation
![image](https://user-images.githubusercontent.com/16399079/207512272-d11d05c4-c7e6-4b7b-a8f6-9215e88ea0b6.png)

Magic tool is not installation,
referring Nickson Jose repsotory for fixes https://github.com/vjkr/openlane_build_script
redirecting to Kunal Ghosh repository https://github.com/kunalg123/vsdflow.git for vsdflow. Hoping the workshop i attended AdvancedPhysicalDesign workshop will be beneficial now
 
 This should look like this
 ![image](https://user-images.githubusercontent.com/16399079/207515701-866f12ab-af79-4ca9-9ae3-ab12a3bc3609.png)

# :)
Seems there was an easier way for installing tools using VSDFLOW. Now 2 versions of installations are in progress.
Lets check the shortcomings in either of them referring to YouTube resources. As workshop videos arent freely available.
# Completed VSDFLOW installation- Update though success message is displayed. qflow didnt get installed. There are errors in the terminal window saying disk full. Checking storage shows storage is almost full. 20GB is not Enough!!!!!!!!!!!!!!
I will delete whole VSDFLOW FOLDER as it is hampering smooth operation of VM.
Hoping to learn sky130 using youtube resources
![image](https://user-images.githubusercontent.com/16399079/207550479-1c263437-1cce-49ca-995a-c469d1845cf6.png)

# Planning to release completed installation as an ISO file
</details>

<details>
<summary># openlane-inverter (stepwise study) NEW vsdflow installation</summary>
 inverter testing successful. Only verilog file and config.json file are input!!!!
 All steps completed without errors or warnings!
 
 ![image](https://user-images.githubusercontent.com/16399079/219607641-c3801c66-2b03-42d5-906f-383c2e0e6b30.png)

</details>

# Learning stepwise following other workshop participants' repos
https://gitlab.com/gab13c/openlane-workshop

## 1. Invoke openlane using 'make mount' and interactive flow
![image](https://user-images.githubusercontent.com/16399079/219614381-8fc51f25-b7f2-4939-8684-be3138776761.png)

start openlane, prep design

## 2. prep design throwing error. Maybe prep was specifically for vsd workshop. 
## 3. Understanding config file. 
new installation of openlane designs have config.json files.
These files look similar to config.tcl.
./flow.tcl -design invconfig completes RTL2GDS flow.
But editing json file with 0 die area thorws below error!!!
![image](https://user-images.githubusercontent.com/16399079/221159264-12033d03-a5c7-4c20-bd38-9b8ba1794cc9.png)

## 4. Trying to learn step by step!
## 5. Synthesis

I could run only synthesis step by referring an interesting issue in openlane https://github.com/The-OpenROAD-Project/OpenLane/issues/805

![image](https://user-images.githubusercontent.com/16399079/221164462-10fb50bb-423b-4cba-8d0f-92125976e41a.png)

