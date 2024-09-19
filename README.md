# tesla ha
Put the images in the www folder of you home assistant and copy the yaml from the picture-elements.yaml
<br>
![doors_opens - small](https://github.com/user-attachments/assets/aeb7a3a1-546a-470b-b0de-a7cc3858dec9)
![doors_open_with_tire_pressure - small](https://github.com/user-attachments/assets/32a9c75d-6f0d-4380-9100-7033e1b757c0)
![Driving - small](https://github.com/user-attachments/assets/3c861d47-b18c-42be-be40-d22becfd7b9b)
![scheduled_charging - small](https://github.com/user-attachments/assets/8a45693d-215c-4658-b0b5-639f8aa396d0)
![charging - small](https://github.com/user-attachments/assets/f329b607-8d2c-43c9-8283-4336b8b27f1e)


The picture element in Home Assistant can visually represent the following:

<ul>
<li><b>Door status</b>: If a door is open, it will be displayed on the image.
<li><b>Battery level</b>: The top line indicates battery charge with color coding:
<ul>
  <li>0-20% = Red
  <li>20-50% = Orange
  <li>50%+ = Green
</ul>
<li><b>Top left</b>: Displays the outside temperature.
<li><b>Top right</b>: Shows the car's status (driving, offline, online, charging, etc.).
<ul>
  <li>Below that: Odometer reading.
  <li>Below the odometer: An icon to show or hide tire pressure.
  </ul>
<li><b>Frunk and trunk</b>: Displays the status (open/closed).
<li><b>Climate control</b>: When turned on, a green fan icon is shown.
<li><b>Battery and range</b>: Displays the battery percentage and the estimated range.
<li><b>Inside temperature</b>: Displayed in the center of the image.
<li><b>Car lock status</b>: Shows an icon for the lock status—gray when locked, green when unlocked.
<li><b>Driving mode</b>: While driving, the speed and navigation destination with ETA are displayed.
  <li><b>Charging port status</b>: The image shows whether the charging port is open or closed.
  <li><b>Car plugged in</b>: If the car is plugged in but not charging, a blue cable icon is displayed, along with a note that scheduled charging is starting.
  <li><b>Car charging</b>: When the car is charging, a green cable icon is shown.
    <ul><li>At the bottom: The charging speed, energy added during the session, and the time remaining until the charge limit is reached are displayed.</ul>
</ul>







