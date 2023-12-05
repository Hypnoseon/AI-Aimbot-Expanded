**CURRENTLY ONLY MAIN_TENSORRT.PY WORKS**, For Arduino Leonardo No need for USB Host Shield as the only reason it was added was to bypass games blocking mouse events.

**MAKE SURE TO HAVE PYTHON VERSION 3.11**
## Expanded AI Aimbot by Rootkit: Expanded Edition

### Features

1. **Changed to Manual Trigger Mode**: To activate aiming, simply hold down the Caps Lock key. This provides more control, as it will not automatically aim.

2. **Automatic Game Detection**: The aimbot can now automatically detect and adapt to the game you are playing. To enable this feature, set the configuration to `true`. For example, if you're playing "Farlight 84", the aimbot will automatically select that game. If you prefer manual selection, set this to `false`.

3. **Field of View (FOV) Circle Adjustment**: The default size of the FOV circle is set to 100. The aimbot will only target enemies within this circle. If an enemy is outside of this specified FOV, the aimbot will not move mouse. You can see the FOV circle if visuals are turned on.

4. **Arduino Leonardo Support**: For those who have an Arduino Leonardo, enable support by setting the corresponding configuration to `True`. If you don't use an Arduino Leonardo, keep this setting as `False`, and the aimbot will default to using the win32 library for mouse movement.

### Configuration Guide

config.py

### Future Updates

- [ ] Easy Model Picker
- [ ] Prediction when enemy moves x,y,z - useful for low fps
- [ ] Trigger Bot
- [ ] Config UI
- [ ] Onnx, Torch Support
- [ ] Kalman filter


### If using Arduino Leonardo, Upload sketch in Mouse.ino
