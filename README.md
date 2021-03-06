# KlipperScreen
KlipperScreen is an idea based from [OctoScreen](https://github.com/Z-Bolt/OctoScreen/), but instead of needing OctoPrint or to compile go, KlipperScreen is python based and interacts directly with [Moonraker](https://github.com/arksine/moonraker), Klipper's API service.

Current feature list:
 - [x] Homing
 - [x] Preheating
 - [x] Job Status and control
 - [x] Temperature control
 - [x] Extrude control
 - [x] Fan control
 - [x] Disable steppers
 - [x] Configure Z Offset using PROBE_CALIBRATE
 - [x] Print tuning (Z Babystepping, Speed Control, Flow Control)
 - [x] Manual bed leveling assist
 - [x] Using thumbnails from prusa on job status page
 - [x] Scale UI based off of resolution
 - [ ] Better system panel
 - [ ] Wifi selection

[Changelog](docs/changelog.md)

### Required Hardware
KlipperScreen should run on any touchscreen that you can connect to a computer. The required video driver may be
slightly different depending on what model you get. KlipperScreen will scale to the resolution of the screen being used.
However, three resolutions are tested during development: 1024x600, 800x480, 480x320.

There are no recommended screens, but there are several screens that work with KlipperScreen. They include screens that
use HDMI/USB, Raspberry Pi GPIO, or the Rapsberry Pi DSI (ribbon cable) port.

### Links

[Installation](docs/Installation.md)

[Configuration](docs/Configuration.md)

[Panels](docs/panels.md)


### Sample Panels

Main Menu
![Main Menu](docs/img/main_panel.png)

Job Status
![Job Status](docs/img/job_status.png)
