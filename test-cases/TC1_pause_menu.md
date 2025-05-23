# TC1 - Pause Menu Functionality

## Objective:
Verify that the pause menu opens correctly and all options function as expected with both keyboard and mouse inputs.

## Pre-Conditions:
- Game is running in active gameplay state.
- Input method: Keyboard + Mouse.

## Test Steps:
1. Launch the game and enter gameplay.
2. Press `Esc` to open the pause menu.
3. Navigate the options using arrow keys.
4. Press `Enter` to select each option:
   - Settings
   - Continue
   - Title Screen
5. Try using the mouse to navigate as well.

## Expected Results:
- Pause menu opens immediately when `Esc` is pressed.
- All options are selectable via keyboard.
- Submenus (like Settings) open and close correctly.
- "Continue" resumes gameplay smoothly.
- "Title Screen" brings player to main menu cleanly.

## Actual Result:
- Pause menu opened instantly with `Esc`.
- All menu items functioned correctly.
- Settings menu opened and closed properly.
- Continue and Title Screen worked without issues.

## Status:
Pass

## Notes:
- Gameplay responsiveness was consistent before and after pausing.
- Test was recorded using OBS (video saved in `/recordings/TC1_pause_menu_test.mkv`)