Latest firmware:

-- enc_Thanos4U_2560_SH_4dof_v1_02_fix9-4.zip - 
--------------------------------------------------
-
--- Fixes for v1_02 fix9-4     5/18/2025
- Fixed power off-on with recalibration for vertical actuators
- Restoring defaults with DIP switch1 to ON (Secondary role), sets Autopark to 50% for the actuators
- Horizontal actuators calibration sequence has been updated, to non blocking, to remedy for power spikes due to torque
-

--- Simhub integration release
- Improved Power Saving function that can
 1. Power OFF and ON Vertical actuators, Power OFF only if parked to 0% 
 2. Power OFF and ON Horizontal actuators

- Added Option to adjust Backtrack of the motor upon calibration from home position. Allows to set the backtrack small enough to avoid having drops when power is turned off.
- Added option to skip Standby state and move the actuators directly to Park position upon finishing the motion tasks.
- Added numerous automation and feedback regarding integration with Simhub, to automate start-stop of the whole platform, and even power off servos on exit or when the motion is idle. A list of the available option will appear on Simhub if supported by the firmware. The new automation allows for very smooth transitions between playing game, or pausing, or handling estop.

- This firmware update will restore factory defaults, to force change of some parameters to work better with Simhub automation. If you have eRacing Lab actuator kit, you can restore the factory defaults that fit best for the actuators, by holding DOWN direction button and press-release the RESET button (150mm stroke) 

- The current Config tool will be able to adjust the basic parameters until new one is released to give access to power saving parameters, backtrack options and extra belt tensioner options.

- some Simhub screenshots:
  
  
![Alt Text](https://github.com/tronicgr/Thanos4U-firmware/blob/main/Latest_Firmware/media/Thanos4U_SH_screen1.jpg)
![Alt Text](https://github.com/tronicgr/Thanos4U-firmware/blob/main/Latest_Firmware/media/Thanos4U_SH_screen2.jpg)
![Alt Text](https://github.com/tronicgr/Thanos4U-firmware/blob/main/Latest_Firmware/media/Thanos4U_SH_screen3.jpg)
![Alt Text](https://github.com/tronicgr/Thanos4U-firmware/blob/main/Latest_Firmware/media/Thanos4U_SH_screen4.jpg)  

-- enc_Thanos4U_2560_4dof_v1_02_fix8.zip 
--------------------------------------------------
- Added updated support for Config tool up to 500mm stroke and other fixes

-- enc_Thanos4U_2560_4dof_v1_01_fix6.zip 
--------------------------------------------------
- Now you can use the up/down buttons to adjust speed of manual testing the actuators (DIP 3&4 set to ON position)


-- enc_Thanos4U_2560_4dof_v1_01_fix5.zip 
--------------------------------------------------
- Rewrite of the servo control engine for smoother and accurate change of direction.


-- enc_Thanos4U_2560_4dof_v1_01_fix2.zip 
--------------------------------------------------
- Fixed issue that might lockup controller when switching command sets in SRS


### AVRUBD utility preset for Thanos4U controllers:
https://github.com/tronicgr/Thanos4U-firmware/blob/main/Latest_Firmware/Thanos4U_Firmware_update_util_AVRUBD_preset.zip

### Firmware Update procedure video for the Thanos4U controller
https://www.youtube.com/watch?v=4abzyBdgQZI

### INPORTANT notice:
- After loading new firmware, please hold down the "UP" button on the panel and press and release the "RESET" button on the controller to restore default parameters. The Blue LED next to the USB connector, should blink 10 times to indicate successful restoration.


