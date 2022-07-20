# Python Photo Editor

Implementation of Python Photo Editor

*setup*



*example of using from terminal:*

Step 1: install all packages use 
```bash
pip3 install -r requirements.txt
```
Step 2: run program using 
```bash
python photo_editor.py
```

```bash
python3 img_modifier.py -p temp.jpg color_filter=sepia --rotate=45 --resize=200,300
```

**All commands list:**

-  **-p path**:  path to initial image
-  **--rotate**: rotate image to N degrees
-  **--resize**: resize image to W and H
-  **--color_filter**: apply color filter (sepia, black_white, negative)
-  **--flip_top**: flip image from top to bottom
-  **--flip_right**: flip image from left to right

Also there is a UI built with PyQt5 which works for Windows, mac os and Linux.

Use **PyInstaller** to convert it

![ScreenShot](http://i.imgur.com/ZPd2Uzi.gif)

**used libs:**
- Pillow (PIL)
- PyQt5
