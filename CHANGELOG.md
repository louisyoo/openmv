Done:
* Rollback to gtksourceview
* Use MP peripherals
* Add ABI version and check it in the IDE
* Add common cascades to the flash
* Fix changing pixformat bug
* Fix sensor reset
* gc/xalloc race bug
* Fix sensor clock
* Update to MP 1.4.4
* Add udev rules help and check for udev file
* Update USB PID:VID
* Update inf file
* Generate Linux/Windows packages
* Catch and print syntax errors
* Add colorbar mode function
* Optimize the IDE (revert to numpy, use timeout_add etc..)
* Remove obselete #define from mpconfigboard.h
* Write colorbar test
* Fix silkscreen
* Rename Eagle files
* Move misc image functions to image module
* Delay sensor init after USB storage to log errors to file
* Implement get/set pixel
* Fix push/pop scope (re-init mp before running scripts)
* Update examples
* Fix main script FS template in main.c
* Remove global misc functions
* Remove lib folder
* Fix draw_string
* Disable built-in DFU on Windows

Todo:
* Update MLX driver
* Use HW I2C for MLX
* Fix LBP face recognizer
* Add reference papers
* Add pinout image to IDE
* Edge detection or geneirc kernel function
* Development VM ?
* Fix cache issues
* define aliaes for pins
* Document OMV's MP API. 
* Use R, G, B macros in imlib.c
* Use R, G, B lookups in imlib.c
* Setting contrast after brightness
* Send PRs for ADC bugs
* Remove pincfg.h and use mpconfigboard.h
* Use dfu in IDE instead of bin, and simpler upload dialog
* move serial port opening to openmv.py
* Test DFU on Mac/OSX (and fix it if needed)
* Add sensor_snapshot timeout
* Test PWM mappings servos
* Grep for TODOs