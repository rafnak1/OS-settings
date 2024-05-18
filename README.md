# Ubuntu
## Keyboard shortcuts
Terminal
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
Build from source using container; then just `docker cp` the result (result will be in directory structure, so `docker cp` to can just move each file to it's correct destination in the hierarchy). Or just search for binaries from a version after the default input mode feature was added.
