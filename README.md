```bash
echo "deb [trusted=yes] https://github.com/JafarAbdi/ros2-dependencies-builder/raw/stable/ ./" | sudo tee /etc/apt/sources.list.d/JafarAbdi_ros2-dependencies-builder.list
echo "yaml https://github.com/JafarAbdi/ros2-dependencies-builder/raw/stable/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-JafarAbdi_ros2-dependencies-builder.list
```
