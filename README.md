# intro_robotics_labs
Python exercises for the course "Introduction to Robotics"

## Troubleshooting
If you are using WSL and do not see the meshes, you can try adding the following lines to your `.bashrc`:
```bash
export LIBGL_ALWAYS_INDIRECT=0
export LIBGL_ALWAYS_SOFTWARE=1
```
alternatively, try updating the OpenGL drivers (this might break your setup):
```bash
sudo add-apt-repository ppa:kisak/kisak-mesa
sudo apt update
sudo apt upgrade -y
# if you haven't done already
sudo apt install mesa-vdpau-drivers
```
