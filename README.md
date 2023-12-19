**NEW UI** Easier to configurate and run!

**CURRENTLY ONLY MAIN_TENSORRT.PY WORKS**, For Arduino Leonardo No need for USB Host Shield, you can spoof arduino leonardo and it should be just fine. Use USB Host shield, spoof if you want minimal detection.

### Features

1. **Changed to Manual Trigger Mode**: To activate aiming, simply hold down the Caps Lock key. This provides more control, as it will not automatically aim.

2. **Automatic Game Detection**: The aimbot can now automatically detect the game you are playing. To enable this feature, set the configuration to `true`. For example, if you're playing "Farlight 84", the aimbot will automatically select that game. If you prefer manual selection, set this to `false`.

3. **Field of View (FOV) Circle Adjustment**: The default size of the FOV circle is set to 100. The aimbot will only target enemies within this circle. If an enemy is outside of this specified FOV, the aimbot will not move mouse. You can see the FOV circle if visuals are turned on.

4. **Arduino Leonardo Support**: For those who have an Arduino Leonardo, enable support by setting the corresponding configuration to `True`. If you don't use an Arduino Leonardo, keep this setting as `False`, and the aimbot will default to using the win32 library for mouse movement.

5. **Body Part Selector**

6 **Randomized Body Part**

7 **Model picker**

### Configuration Guide

UI

### Future Updates

- [ ] Trigger Bot
- [ ] Onnx, Torch Support


### If using Arduino Leonardo, Upload sketch in Mouse.ino

Run this for Fortnite model

python .\export.py --weights ./fort.pt --include engine --half --imgsz 320 320 --device 0

"Run the Export Script 🏃‍♂️💻 Time to execute export.py with the following command. Patience is key; it might look frozen, but it's just concentrating hard! Can take up to 20 mintues."

Love you Rootkit ❤️


IF YOU WANT TO RUN WITHOUT UI, JUST USE "PYTHON MAIN_TENSORRT.PY", SPECIFY YOUR MODEL IN CONFIG.PY
