# Issue Tracker
XRmonitors public issue tracker

## Frequently Asked Questions

### HP Reverb screens or cameras are flickering

The XRmonitors software adjusts the USB hub power configuration for you to try to reduce that sort of issue.  We have found that unplugging the HMD cable from the headset and replugging it 10 seconds later often resolves this issue.

### XRmonitors features

The currently supported feature set:

* Catered to the needs of professionals intent on using their high-resolution VR headsets for productivity in the workplace.
* Designed for Microsoft Windows Mixed Reality headsets such as the HP Reverb.
* Uses the new OpenXR Runtime provided by Microsoft.
* Does not require installing SteamVR or Oculus software on a workplace PC.
* Multiple monitors placed at the focal distance of each VR headset for optimal eye comfort.
* Virtual monitors are placed 2x farther from the operator than normal monitors, making them more comfortable to look at than normal monitors.
* First class support for Headless Ghost and other fake monitor dongles.  This allows the operator to view private monitors not visible to anyone nearby.
* Monitors curved around the user, without any bezels between them.
* Keyboard shortcuts to recenter monitors above, below or in front.  Allows the user to more comfortably operate their Windows computer while reclining.
* Keyboard shortcuts to increase or decrease virtual monitor pixels per degree (size).  Unlike real monitors, the DPI can be reconfigured at any time.
* Keyboard shortcuts to pan monitor view making it possible to quickly switch between monitors.
* Pass-through cameras using the tracking cameras supporting all Mixed Reality headsets.  The calibration data is stored in the install folder in `camera_calibration.ini` with instructions for manually editing the file if desired.
* Pass-through cameras can be disabled for added focus mode.
* Ergonomics feature to reduce blue light from the display, simulating blue light reducing filter glasses.
* Optimized render paths for same-adapter and different-adapter using D3D11.
* Virtual consoles that can be called up outside of the normal Windows desktop.  Switch between them using look-and-type rather than laborously clicking or using complex keystrokes.

### Planned feature roadmap

* Walkthrough training video for business use.
* Track headset don time and report it in the UI.
* Plugin architecture improved documentation and examples.
* Auto-update banner in the application.
* Add the application to the Microsoft app store.
* Show protected screens (UAC) in VR.
* Prototype logging into the computer in VR.
* Fix fast-moving cursor stuck on old screen.
* Prototype Windows VirtualDesktop feature integration.
* Set Mip level 2 for 4K monitors and level 1 for Full HD monitors.
* Prototype CMAA2 anti-aliasing approach.
* Monitors that are similar physical sizes but different resolutions should look the same in VR.
* Analytics track in-headset hours so we can report on the website.
* Guided ergonomics exercises in HMD: https://www.youtube.com/watch?v=F8_ME4VwTiw
* Prototype integration of some approaches for ergonomics from: http://mid.kaist.ac.kr/
* Integrate a plugin for virtual browsers.

### Collecting application logs

To get more information about an issue:

Logs from the installer are stored in `%ProgramData%/XRmonitors` under `XRmonitorsInstaller*.log`.

Logs from the background service are stored in `%ProgramData%/XRmonitors` under `XRmonitorsService*.log`.

Logs from the desktop UI are stored in `%LocalAppData%/XRmonitors` under `XRmonitorsUI*.log`.

Logs from the VR application are stored in `%LocalAppData%/XRmonitors` under `XRmonitorsHologram*.log`.

### Other issues

Please contact us through one of the options available below.

## How to submit an issue

Select the `Issues` tab at the top.  Browse the existing issues to see if another user has already reported the problem.  Click the `New Issue` button on the right to create a new issue report.

## Business license support

For customers who have purchased a Business license, we offer best effort real-time support and priority for new feature requests.  Support contact information is available in our Email correspondence.

## Community support

The user community may be able to offer help.  To join our real-time chat community, please visit https://xrmonitors.com/slack to receive an invite to our Slack chat channel at https://xrmonitors.slack.com.  We monitor the chat community and offer advice when possible.

We monitor our Twitter account https://twitter.com/xrmonitors for help requests, and we also post information about resolved issues on Twitter.
