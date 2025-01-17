# SETUP

```bash
echo "yaml https://raw.githubusercontent.com/tii-swarm/rosdistro/main/rosdep/arrc.yaml" | sudo tee /etc/ros/rosdep/sources.list.d/10-arrc.list

echo "yaml https://raw.githubusercontent.com/tii-swarm/rosdistro/main/rosdep/$ROS_DISTRO.yaml" | sudo tee -a /etc/ros/rosdep/sources.list.d/10-arrc.list

rosdep update
```