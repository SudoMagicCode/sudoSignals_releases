# Tested On
* Windows 10 Pro

# New Features
* None

# Improvements
* Process can start separately of sudoSignals and still be monitored.
* SudoSignals will continue running when it loses connection to cloud 
and attempt reconnection once network connectivity is re-established.
* WS service port can now be changed in the project.yaml file.

# Bug Fixes
* File paths with spaces now load correctly.
* Issues with autostart and process startup
* Fixed issue with network connectivity causing process to reload endlessly
* Process startup would not launch ableton with selected file.


# Compatibility Warnings
* None
