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

## Nvidia Container Toolkit
If you get the error:
```
Failed to initialize NVML: Unknown Error
```
Then try editing:
```
/etc/nvidia-container-runtime/config.toml
```
By changing `no-cgroups` to:
```
no-cgroups = false
```
And then:
```
sudo systemctl restart docker
```
