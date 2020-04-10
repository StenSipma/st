# Custom ST Build
Heavily Work In Progress!

## Version
st 0.8.2

## Features
TODO

## Patches
Applied in the following order
1. xresources: Success
2. clipboard: Success
3. desktopentry:
   - Patch with -R option. (or accept it in the prompt)
   - Add a st.desktop file yourself
4. scrollback
   a) normal: Success
   b) mouse: Success
   c) mouse-altscreen: Success
   d) mouse-increment: Manual Intervention due to altscreen.  Just change the `1` to `mousescrollincrement` in `mkeys`



####Applied:
- Xresources compatibility
- Primary Cliboard Usage 
	Ctrl+Shift c/v
- Scrollback 
	Mouse or Shift PageUp/PageDown
- Desktopentry 
	With custom st.desktop file

####To Do:
- Alpha
- Copyurl: Some Issues (maybe due to patch being for 8.0.1 ?) Minor Intervention needed.
