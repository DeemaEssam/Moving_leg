# Moving_leg

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
