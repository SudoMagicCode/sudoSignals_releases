# Release
v0.1.91

# Tested On
* Windows 10 Pro

# New Features
* Multiple plugins can now communicate to Dashboard 
* Multiple processes can now be started and stopped from Dashboard
* AutoFill ProgramPath

# Improvements
* Added versioning to configurations.
* Optimization for CPU utilization.

# Bug Fixes
* Offline notifications sending false alerts
* Process without the auto-restart flag would not restart with start command from the Dashboard 
* Processes would not terminate properly with interrupt
* Starter kept cmd window open
* Removed configuration keys that aren't used.
* Default programs not found when available
* Process restarts failed after refefactor. 

# Compatibility Warnings
* None