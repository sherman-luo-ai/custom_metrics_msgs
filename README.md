To install, clone the repository in the /simian directory in the docker container: 
```
cd /simian
git clone git@github.com:erikrosen1/custom_metrics_msgs.git
```

Build the package:
```
cd /simian/custom_metrics_msgs && colcon build --packages-select custom_metrics_msgs
source /simian/install/setup.bash
```
