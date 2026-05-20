# Cloud-Connected-Package-Locker


The purpose of this project was to design a cloud-connected smart locker that only opened once the proper code was remotely entered into it from a smart phone, or if the proper code was entered into it via its keypad. I worked in a team of 6 for this project. 

The hardware included a Raspberry Pi Zero W, servo motor, matrix keypad, magnetic reed switch and a 7-segment display. 

Functionality: 
1) Raspberry Pi Zero W was used as the main brain of the system, running python scripts to interface with our custom iPhone app.
2) The servo motor was used to lock and unlock the locker.
3) The matrix keypad was used to input the security code. If the code was correct, the servo would unlock the locker, otherwise it would stay locked.
4) The magnetic reed switch was used to know when the locker was open, in case someone tried to forcefully open the locker without knowing the security code. A message would then be sent to the user's phone when this happened.
5) The 7-segment display would display the current code the user was inputting into the locker, as well as other helpful information.

<p align="center">
  <img src="https://github.com/user-attachments/assets/02df1184-e795-4c25-958a-42a6f51eb5d8" width="300">
  <br>
  <em>Front of the cloud-connected locker. I laser cut plywood so the 7-segment display and Keypad would fit. </em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/fc096325-d786-40cd-9478-94c647535935" width="300">
  <br>
  <em>Raspberry Pi connected inside the locker.</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0505b04c-75d4-43c3-bb96-6f3c7f492474", width="300">
  <br>
  <em>Bottom-up view of the magnetic reed switch and the servo motor.</em>
</p>



Circuit Schematic of Hardware: 

<img width="883" height="607" alt="image" src="https://github.com/user-attachments/assets/b138aa1d-e1be-4682-a8ae-3e53b6f9d96c" />

## Completed in May of 2022
