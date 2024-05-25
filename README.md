# Ubuntu
## Keyboard shortcuts
Terminal (set font size manually, around 16 or 18)
```
gnome-terminal --maximize
```
Personal Chrome (Shift+Ctrl+Q)
```
google-chrome --profile-directory="Default" --new-window
```
Secondary Chrome (Shift+Ctrl+E)
```
google-chrome --profile-directory="Profile 1" --new-window
```
## Startup Applications
imwheel - avoid killing forward and back mouse buttons (use imwheel to avoid Ubuntu Alt+Tab scrolling issues; use .imwheelrc to keep ctrl + scroll zoom)
```
imwheel -b "4 5"
```
## Mozc
Build from source using container, with bazel flag `--local_resources=cpu=4`

Set half width space
