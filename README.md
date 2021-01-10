# Custom ST Build
Heavily Work In Progress!

## Version
st 0.8.4

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
   - normal: Success
   - mouse: Success
   - mouse-altscreen: Success
   - mouse-increment: Manual Intervention due to altscreen.  
   Just change the `1` to `mousescrollincrement` in `mshortcuts`
   - These 4 are combined into: `patches/st-scrollback-0.8.4-complete.diff` patch
5. font2: Success


### Applied:
- Xresources compatibility
- Primary Cliboard Usage 
	Ctrl+Shift c/v
- Scrollback 
	Mouse or Shift PageUp/PageDown
- Desktopentry 
	With custom st.desktop file
- font2
        Adds a fallback font, which you can point to an Emoji font. 
        (i.e. Google Color Emoji)
        Does need a patch for libxft form AUR 
        [libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/)

### To Do:
- Alpha
- Copyurl: Some Issues (maybe due to patch being for 8.0.1 ?) Minor Intervention needed.
