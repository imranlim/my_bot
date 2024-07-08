## Robot Package Template

This is a GitHub template. You can make your own copy by clicking the green "Use this template" button.

It is recommended that you keep the repo/package name the same, but if you do change it, ensure you do a "Find all" using your IDE (or the built-in GitHub IDE by hitting the `.` key) and rename all instances of `my_bot` to whatever your project's name is.

Note that each directory currently has at least one file in it to ensure that git tracks the files (and, consequently, that a fresh clone has direcctories present for CMake to find). These example files can be removed if required (and the directories can be removed if `CMakeLists.txt` is adjusted accordingly).



## Error 1

raise InvalidLaunchFileError(extension, likely_errors=exceptions)
launch.invalid_launch_file_error.InvalidLaunchFileError: Caught exception when trying to load file of format [py]: No module named 'xacro'

## Solution 1
sudo apt install ros-foxy-xacro

## Error 2

Package 'joint_state_publisher_gui' not found

## Solution 2
sudo apt install ros-foxy-joint-state-publisher-gui

 
 
