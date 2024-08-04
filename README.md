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

| 1 | 2 |
| -- | -- |
| <img width="424" width="324" alt="1-moving foot right" src="https://github.com/user-attachments/assets/ba851b82-b68e-4618-bf5b-077ca63b6d55"> | <img width="424" width="324" alt="2-moving right leg forward" src="https://github.com/user-attachments/assets/b6cf52ab-cc83-43a9-a444-27fe140d4887">|


| 3 | 4 |
| -- | -- |
| <img width="424" width="324" alt="3-move right right" src="https://github.com/user-attachments/assets/5bcf4135-9b5b-4657-b736-05b8be45f441"> | <img width="424" width="324" alt="4-foot back" src="https://github.com/user-attachments/assets/fcfb2d85-4f62-424f-a7d4-7460817c57ba">

| 5 | 6 |
| -- | -- |
|<img width="424" width="324" alt="5-move right back" src="https://github.com/user-attachments/assets/89154f08-d786-4534-8938-80e328beaf85">
 | <img width="424" width="324" alt="6-move left back" src="https://github.com/user-attachments/assets/9e43d120-c1f9-4102-bcf3-d67c2c8be036"> |


***Then, the same steps to move the left leg***
