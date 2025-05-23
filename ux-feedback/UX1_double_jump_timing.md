# UX1 - Double Jump Timing Feels Inconsistent

## Summary
Double jump feels unresponsive or weak when the second jump input is pressed too quickly after the first. While the mechanic works, the resulting motion feels like a short single jump which may confuse players.

## Environment
- Platform: PC (Steam)
- Input: Keyboard
- OS: Windows 10
- Game Version: Latest (as of May 2025)

## Observations
- Rapid double-tap of jump results in a second jump very close to the ground.
- Animation plays, but arc is too low to visually distinguish from a single jump.
- Creates confusion during platforming or panic jumps.

## Expected Behavior
- Clear separation in arc or timing between jumps to ensure feedback feels responsive.
- Visual or audio cues reinforcing the double jump action.

## Actual Behavior
- Input is technically registered, but feedback is unintuitive.
- Players may assume the second jump failed or was not registered.

## Suggested Improvements
- Add a short delay between jump triggers to space out the animation.

## Severity
Very Low- this is not a bug, but a usability/feedback improvement.

## Notes
- Tested in multiple areas with platforming. Consistent behavior. Occurs more frequently with fast input or panic jumps during enemy encounters.
- Test was recorded using OBS (video saved in `/recordings/UX1_double_jump_timing.mkv`)