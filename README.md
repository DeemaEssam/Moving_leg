# Moving_leg

![image](https://github.com/user-attachments/assets/f8efe95a-c519-4f4a-9786-b80ae32cfa77)


## Pseudocode
```ruby
INITIALIZE:
  Attach hip1 to pin 3
  Attach knee1 to pin 5
  Attach ankle1 to pin 6
  Attach hip2 to pin 9
  Attach knee2 to pin 10
  Attach ankle2 to pin 11

  SET initial position for all servos to 90 degrees

LOOP:
  // Step 1: Move the right foot to the right
  SET ankle1 to 60 degrees

  WAIT 500 milliseconds

  // Step 2: Move the right leg forward
  SET hip1 to 45 degrees

  WAIT 500 milliseconds

  // Step 3: Move the right leg to the right
  SET knee1 to 45 degrees

  WAIT 500 milliseconds

  // Step 4: Move the right foot back to its previous position
  SET ankle1 to 90 degrees

  WAIT 500 milliseconds

  // Step 5: Move the right leg back
  SET hip1 to 90 degrees

  WAIT 500 milliseconds

  // Step 6: Move the right leg to the left again
  SET knee1 to 135 degrees

  WAIT 500 milliseconds

REPEAT loop

```

<img width="424" alt="1-moving foot right" src="https://github.com/user-attachments/assets/ba851b82-b68e-4618-bf5b-077ca63b6d55">

<img width="482" alt="2-moving right leg forward" src="https://github.com/user-attachments/assets/dbc7fcc3-f3d7-4cd2-ae4a-721fe2954f3d">

<img width="497" alt="3-move right right" src="https://github.com/user-attachments/assets/edfbec8d-9b0d-47ef-94d8-28170ef49b8f">

<img width="431" alt="4-foot back" src="https://github.com/user-attachments/assets/09b14ca9-58ae-4062-8170-b140003ced06">

<img width="427" alt="5-move right back" src="https://github.com/user-attachments/assets/89154f08-d786-4534-8938-80e328beaf85">

<img width="405" alt="6-move left back" src="https://github.com/user-attachments/assets/9e43d120-c1f9-4102-bcf3-d67c2c8be036">
