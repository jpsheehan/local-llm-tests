# Circuit Racer

## Features

- [x] AI cars should have their own racing lines so that they don't keep colliding with each other.
- [x] All cars that finish the race shouldn't stop at the end of the race. Instead they should become uncontrollable and deccelerate normally.
- [x] The lap times on the UI should have another digit of precision
- [ ] Add a sound effect for colliding with other vehicles
- [ ] Allow the player to reverse their vehicle by holding the down or 'S' key after they are stopped.
- [x] Add sound effects for:
    - [x] Braking
    - [x] Accelerating
    - [x] Completing a lap
    - [x] Completing the penultimate lap
    - [x] Finishing the race
    - [x] Counting down to the race start
- [x] Add collision detection
- [x] Add a list of lap times to the UI.
- [x] Add a new first-person camera angle and make it the default. The player should be able to toggle between them with 'C'.
- [x] Place all the cars on a starting grid with the player at the rear.

## Bugs

- [ ] The player's position briefly shows as '4th' place just before they cross the finish line even when they're not in that position
- [x] The player's finishing position shouldn't change after the race has finished.
- [x] Vary the acceleration sound effect so that it doesn't sound so "droning"
- [x] The starting positions of the AI players should match their lateral offsets.
- [x] After colliding, the AI cars are not able to go faster than they were when they stopped colliding.
- [x] The player's speed is still set to the speed they were going when they finish the race rather than zero.
- [x] The game sometimes doesn't detect when the player completes a lap.
- [x] When switching between camera modes, the camera should smoothly interpolate between the two rather than snapping.
- [x] The angle of the NPC cars is wrong.
- [x] The angle of the barriers is wrong.
- [x] The player is too fast.
- [x] The game ends before the player crosses the finish line.
- [x] The player's racing position is often not correct.
- [x] The player's wheels still spin after they have finished the race.
- [x] The minimap has a little white line on the player's circle.
