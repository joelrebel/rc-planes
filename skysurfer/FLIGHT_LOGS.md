####

#### 2:30 PM 28th June 2020

### Location
Waterlandplien 
https://goo.gl/maps/2Hqfayy7JxPrkgEbA


### Weather
23 Degrees Celsius
2 BFT wind SW 
Cloudy skies with mild rain

### Log

Three launches and one manual landing, 2 INAV controlled landing,

### Issues

- FPV video dropped out intermittently, although less than earlier

### Learnings

- Return to home should be set for a short while or INAV initiates landing sequence.
- The wirings should be directly soldered instead of header wires,
  these are problematic over time and are most likely the cause for the FPV video
  dropping out when the servos draw power.

#### 1:00 PM 20th June 2020

### Location
Almere poort - lawsonpad
https://goo.gl/maps/BCzeABWoX7KDmC457

### Weather
18 Degrees Celsius
3 BFT wind West
Clear sunny skies

### Log

Four launches, 3 landings were sketchy due to high winds, 1 crash into a tree,
the final flight was a launch which ended up in a tree because of pilot error,
the wind heading west may have been a contributing factor for the tree crash.

### Issues

- FPV video dropped out periodically - while the OSD is recieved, the camera video drops out
- GPS ground was disconnected during previous maintenance/fixing
- In the third flight the battery level was at 11v, the 1800 mAh Tattu battery ended up being over-discharged
- AOMWAY FPV goggles records video without OSD - even thought the OSD is recieved by the goggles

### Learnings

- Aircraft needs to be level when powered on for INAV calibration
- Ensure battery percentage remaining capacity is exposed in the OSD
- INAV OSD output needs to be set to NTSC for AOMWAY to record video with OSD
- Plane ends up in Landing mode if Return to home is activated long enough
- Need to spend more time on the simulator for landing practice in windy senarios

#### 1:15PM - 5:00PM 26th April 2020

### Location
Almere poort - lawsonpad
https://goo.gl/maps/BCzeABWoX7KDmC457

### Weather
15 Degrees Celsius
1 BFT wind North
Clear sunny skies

### Plane model

Skysurfer running INAV

### Log

The weather was good, low winds, clear sky, good temperatures,
was finally able to maiden the flight - with 4 take offs and landings !

The elevon needed to reversed, this was fixed in INAV.

Had help for the first take off, which was manual done by Joseph,
we tested if the plane did well in the Angle mode and Return To Home modes,
the tests went well, the plane did very well.

Total flight time estimate (all flights combined) was about 1 hour,
ran through 3 1550 Lipo batteries.

### Issues
- Camera video feed kept failing - evident in video, seems related to roll servo controls.
- Plane needs to be laminated so the foam isn't damaged on each landing
- Radio control reciever seemed to have dropped out in the last few minutes - on the last flight, its unclear what went wrong.
- On the last flight, the plane went into Landing mode and could not be controlled, this may be related to loss of signal,
  luckily it landed in a safe place and the landing was handled by INAV very well.

### Learnings

- When powering on the flight controller and components, ensure the plane is level,
  so the calibration is done right.
- When on the ground INAV will not Arm the motors if Return To Home is set
- The launch mode sequence needs to be done right - in this order,
   1. Set Angle mode
   2. Set Arm motors
   3. Set Launch mode
   4. Set throttle to 50%
- If launch mode set correctly, the main motor will refuse to throttle and will
  wait for the trigger - thrusting the plane forward.
- Its ideal to have launch mode and Return to Home on different toggle switches,
  so both can be set - the plane will then gain altitude and Return to home - loiter above.
- The plane will go out of launch mode if its triggered and was not thrown.
- Follow the INAV arrow, its easy to lose orientation/sense of location when controlled over FPV
- LOS controls are harder when the plane has the sun behind it.
- Practice landings in simulator
- Add RSSI signal for radio reciever

### Fixes to be done

- Set Launch mode on a different switch
- Fix wiring for Camera - replace VTX and camera cabling
- Check and recheck radio transmitter controls
- Add a better antenna for VTX
- Move VTX to the wing so its not on top of the motor wires.
- Camera needs to face downwards a bit more or be moved forward, check the video recording.
- Battery needs to be stuck with velcro instead of double sided tape - its easier to deal with.

#### 12:30 PM 14th Sept 2019

### Location
Close to Ijdoornlaan Amsterdam 1024KM, Netherlands
https://goo.gl/maps/FCw7MAuRCjGvvgDx5

### Weather
19 Degrees Celsius
2 BFT wind South
Clear sunny skies

### Log

The weather was in favour, low winds, clear skys, good temperatures,
the end result was a bad launch with the plane landing right in a canaal.

The plane was itself was ready to fly, although a few things were unexpected/unprepared,

- Flight checklist
 - This was left at home
- Transporting the wings of the plane required help from Johannes Kohen
- Flight prep time was atleast an hour
- Prop was mounted incorrect - thrust wasn't enough
- Motor was wired incorrectly - thrust was reverse
- I was unable to initiate launch mode by causing a jerk on the plane
- Its unclear if we have enough satellites for launch
- On launch we have to control pitch quickly to prevent a stall

### Learnings / action items

### Pre launch
- Test launch mode works well in advance
- Ensure the launch area is away from water bodies
- We need good rubber bands to hold down the canopy(?)
- For the first launch its a good idea to use manual mode and switch to angle/horizon mode later?
- If theres enough thrust at full throttle, the rudder and 

### Post launch
- Launch with high ish throttle
- Pitch up until we have some altitude, and then level pitch
