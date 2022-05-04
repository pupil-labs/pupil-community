# pupil-community

This repository is a `README` only repository for community contributed projects, forks, plugins, scripts, and videos using [Pupil](https://github.com/pupil-labs/pupil) - open source eye tracking platform.

## Contributing
Want to add your project, fork, plugin, or script to this list? Fork this repo and make a [Pull Request](https://github.com/pupil-labs/pupil-community/pulls) with a link and short description in the README file.

Want to add your demo video to this list? Make an [issue](https://github.com/pupil-labs/pupil-community/issues) with the Youtube link and the maintainers will add the video to [this Youtube playlist](https://www.youtube.com/watch?v=X_BalnBOcpk&list=PLi20Yl1k_57pr6zl9D6JHSrOWyLXxsTQN).


## Plugins
Install instructions: https://docs.pupil-labs.com/developer/core/plugin-api/#adding-a-plugin

### Pupil Detector Plugins
Requires Pupil v2.6 or higher.
- [`artificial_2d_pupil_detector.py`](https://gist.github.com/papr/ed35ab38b80658594da2ab8660f1697c): Example pupil detector plugin that generates artificial pupil data
- [`custom_2d_pupil_detector.py`](https://gist.github.com/papr/b938ddc6315525d0f03da3668568e75c): Example pupil detector plugin that extends the default 2D detector

### Video Backends
- RealSense D400 Source v1.22 - A port of the old realsense2 plugin (for RealSense D400 series cameras) to work with the new video source framework in Pupil Capture v1.22.
    - Up to Pupil Capture v2.2 ([here](https://gist.github.com/pfaion/080ef0d5bc3c556dd0c3cccf93ac2d11))
    - From Pupil Capture v2.3 ([here](https://gist.github.com/romanroibu/c10634d150996b3c96be4cf90dd6fe29))
- [Pupil Video Backend](https://github.com/Lifestohack/pupil-video-backend) - Streams Video from another computer through the network to your computer where pupil capture software is running.
- [Ximea Camera Plugin](https://github.com/vdutell/PupilXimea) - A plugin to preview and record frames from Ximea Cameras using XiAPI.

### Calibration Choreographies and Gazers
- [Dual-monocular 2D and 3D Gazers](https://gist.github.com/papr/5e1f0fc9ef464691588b3f3e0e95f350) - 2D and 3D gaze mapping plugins that map all pupil data monocularly. Recommended if when investigating strabismus or similar conditions. Requires Pupil v2.2 or higher.
- [Dual-display HMD calibration choreography and gazer](https://gist.github.com/papr/fcbafd5cf748c9b11e64a4dd37ec8e9a) - Dual-monocular 2d calibration, but with the possibility to calibrate different target coordinate systems for each eye.
- [Nine-point calibration choreography](https://gist.github.com/papr/339dcb08caef45d3798a68aa4e619269)
- [Custom calibration confidence threshold](https://gist.github.com/papr/04b9e4b9c1758c3701bf260dfa67f83f)


### Minimal Examples
- [Custom Data example](https://gist.github.com/papr/079a520a1f2a31b1b73963feb7037995) - Pupil Capture plugin that demonstrates how to publish custom data via the Network API and have it saved during a recording
- [Online Task Proxy](https://gist.github.com/papr/0eaba2bc70755ffb1ad05385a3458a07) - Example plugin that shows how to use the `Task_Proxy` class in Pupil Capture
- [Unix Time Sync](https://gist.github.com/papr/87c4ab1f3b533510c4585fee6c8dd430) - Example plugin that shows how to synchronize the Pupil clock to Unix time
- [Depth Frame Accessor](https://gist.github.com/papr/0f13943e2aebd768ab6b1508d466caae) - Example plugin that shows how to access the 16 bit depth data of Realsense frames in Capture
- [TaskLib Example](https://gist.github.com/ckbaumann/c21501ce28c4ba3cdd7bdf19fabb6d09) - Example plugin that demonstrates basic `task_lib` usage.

### Pupil Player Visualizations
- [Single gaze point visualization](https://gist.github.com/papr/d364b379b1b311fdd185bc383f43ef95) - Pupil Player plugin that only visualizes the gaze point that is closest in time to the current frame
- [Render frame index into video image](https://gist.github.com/papr/c123d1ef1009126248713f302cd9fac3) - Pupil Player plugin that renders the current frame index into the video frame
- [Render date time into video image](https://gist.github.com/papr/7d84267e9e1284b5763ac3afb1732494) - Pupil Player plugin that renders the recording time of the current frame
- [Video overlay with manual temporal-alignment option](https://gist.github.com/papr/ad8298ccd1c955dfafb21c3cbce130c8) - Allows to synchronize unaligned videos

### Others
- [LabStreamingLayer integration](https://github.com/labstreaminglayer/App-PupilLabs/)
- [Annotations without log messages](https://gist.github.com/papr/7b940b2c02e05135f59d599a6a90c5f6) - Pupil Capture plugin that does not display a log message when receiving an annotation. This is helpful if you need to receive many annotations.
- [Gaze from recording with manual offset correction](https://gist.github.com/papr/d3ec18dd40899353bb52b506e3cfb433)
- [Gaze-controlled VLC Player - gvlc](https://github.com/MPIK-COMMS/gcvlc) - Gaze-controlled VLC player using Pupil Capture.
- [Pupil Labs usybus Controller](https://github.com/Lahorde/pupil-labs-usybus-controller) - This plugin exports pupillabs eye tracking gaze to [Ivybus](http://www.eei.cena.fr/products/ivy/).
- [Pupil progs](https://github.com/SGBon/pupil-progs) - Python helper scripts used with Pupil (post-hoc and real-time).
- [@cpicanco's Pupil Player Plugins](https://github.com/cpicanco/player_plugins) - A collection of visualization and analysis plugins for Pupil Player.
- [@cpicanco's Pupil Capture Plugins](https://github.com/cpicanco/capture_plugins) - A collection of plugins for Pupil Capture.
- [Pupil 2D Detection Preview](https://github.com/Christopher22/pupil_preview) - Plugin which shows a scrollable gallery of eye images with 2D pupil detection after a recording stops. Its purpose is to get a brief visual insight of how good the detection will be, when the online detector was disabled due to perfomance or stability reasons. The eye images are saved with a fixed time interval in a subdirectory of the recording. It also shows the usage of changing the detection properties and accessing the GPOOL in a plugin. The frame publisher has to be enabled during recording.
- [pupil-t265](https://github.com/vedb/pupil-t265 "pupil-t265") - Calibrate, record and export tracking data from the Intel RealSense T265 tracking camera.

## Projects & Forks
- [PyPlr](https://github.com/PyPlr/cvd_pupillometry) - Many-featured Python library for researching the pupillary light reflex with Pupil Core. Easily time-stamp any light stimulus with the World Camera. 
- [Pupil Labs Motion Capture Trigger](https://github.com/N-M-T/Pupil-Labs-Mocap-Trigger) - Use a low-cost Arduino microcontroller to synchronise motion capture systems (e.g. Vicon/Qualisys) with the Pupil Core Mobile eye tracker.
- [Plugin to Perceive the Object in Focus](https://github.com/jesseweisberg/pupil) - Real-time object-detection plugin that integrates eye-tracking (fixation data) to identify which object the user is currently fixated upon. An example of its potential is shown in controlling grasps of a robotic prosthetic hand. Part of the [Therabotics Project](https://www.jesseweisberg.com/therabotics/)
- [PolyMouse](https://github.com/trishume/PolyMouse) - PolyMouse is a fusion of gaze tracking and head tracking to achieve hands-free pointing. It does this by using eye gaze to quickly determine an imprecise area of interest and then uses small head movements to refine the position of the cursor onto a small target.
- [Asistiva](https://github.com/hookdump/asistiva) - a set of tools for creating amazing web apps optimized to be used through different input methods (i.e. including eye-tracking, head-tracking, button-less mouse, adapted switches, etc).
- [Focal](http://stewartgreenhill.com/articles/focal/) - Focal is an experimental eye-tracking musical expression controller which allows hands-free control over audio effects and synthesis parameters during performance. A see-through head-mounted display projects virtual dials and switches into the visual field.
- [Graph viz eye tracker](https://github.com/Saftophobia/graph-viz-eye-tracker) - Creating a gaze-aided graph navigating application using Unity3D and Pupil-lab.
- [Optical Dimension Spatial Thinking - ODST](https://github.com/Ruzzy77/ODST) - Gaze controlled interface using gaze data and voice recognition.
- [PupilCamC++](https://github.com/themrx/PupilCapture) - Interface for capture of Pupil labs cameras with C++, primarily for windows
- [Pupil-lib Trial/Event Extraction Library](https://github.com/gmierz/pupil-lib-python) - A flexible tool for conducting high precision event based research analysis with Pupil Labs eye trackers. See [here](https://github.com/gmierz/pupil-lib-python/blob/master/README.md#running-a-compatible-experiment) for how to run an experiment that produces data compatible for this library. A [Matlab version](https://github.com/gmierz/pupil-lib) is also available.
- [Mobile Gaze Mapping](https://github.com/jeffmacinnes/mobileGazeMapping) - Automatic gaze mapping between world camera and a fixed reference stimulus. This tool provides automatic detection of a 2D target stimulus in a mobile eye-tracking recording, and translates recorded gaze data from the world camera to the fixed coordinate system of the stimulus itself. 
- [JupilLabs](https://github.com/auejin/JupilLabs) - A Processing(Java) binding for extracting data from pupil-labs with jeromq and msgpack-java
- [Save data where users looked](https://github.com/FJK22/pupil-SaveData-WhereUserLooked) - A script that allows to save data where the user has looked using Pupil in a Unity Application

## Scripts
### Real-time Network API clients
- [pupil-remote-php](https://github.com/ignacioxd/pupil-remote-php) - A simple PHP remote control client for the Pupil eye tracker software.
- [Lab Matlab Control](https://github.com/TheGoldLab/Lab-Matlab-Control/tree/62d56585ef2fda3c17045dfcdc69e159eb317a38) - Custom utilities for experimental control.
- [Pupil Pascal Client](https://github.com/cpicanco/pupil-fpc) - Free Pascal requester and subscriber clients for Pupil.
- [Pupil MatLab Client](https://github.com/matiarj/pupil-helpers/tree/matlabAddV2/pupil_remote/Matlab_Python) - MatLab subscriber client for Pupil.
- [Pupil Middleman](https://github.com/mtaung/pupil_middleman#pupil-middleman) - A middleman client written in Python. This client can be used to interface with Pupil Capture and other sytems and languages that do not natively support ZeroMQ. 
- [Network Topic Monitor](https://nbviewer.jupyter.org/gist/pfaion/115e13e822b308f0896b59bc7971d676) - A very simple network topic monitor. Shows notification count for every topic and how long ago the last notification was received.
- [OptiTrack and Pupil Labs Python Recorder](https://github.com/mdfeist/OptiTrack-and-Pupil-Labs-Python-Recorder) - A simple python script that records data from Pupil Labs and OptiTrack.
- [Surface OSC Bridge](https://github.com/papr/pupil-helpers/tree/oscbridge/pupil_remote/OSC_Python) - Redirects
surface data using the [`OSC` protocol](http://opensoundcontrol.org/introduction-osc).
- [IPC Backend Simulator](https://gist.github.com/papr/49f58a894364dd94b23c53e6bc6929d0) - Simulates the Network API of a Pupil Capture instance, publishing data from a provided recording

### Post-hoc Analyses
- [Generate Pupil-Player-compatible recording from externally recorded video](https://gist.github.com/papr/bae0910a162edfd99d8ababaf09c643a)
- [Offline Gaze Mapping Tools for Pupil Labs Glasses](https://github.com/jeffmacinnes/pl_gazeMapping_offline) - Offline Gaze Mapping Tools for Pupil.
- [Eye Tracking Research Data Analysis ](https://github.com/qalhata/Eye-Tracking-Research-Fixation-EDA-PupilLabs-Data-) - Python pupillometry analysis scripts to analyize pupil_data. 
- [extract_diameter.py](https://gist.github.com/papr/743784a4510a95d6f462970bd1c23972) - Extract 2d and 3d (if available) pupil diameters for a set of given recordings
- [extract_surfaces.py](https://gist.github.com/N-M-T/b7221ace2e7acf0c0c836773a3b4cf7c) - Extract gaze and fixations on surfaces (if available) for a given set of recordings
- [extract_blinks.py](https://gist.github.com/papr/40ba7d99f572bc0fe388a81aa2f87424) - Extract blinks for a given set of recordings
- [batchExportPupilLabs](https://github.com/tombullock/batchExportPupilLabs) - Batch exports prercorded data as csv for a set of given recordings
- [Head pose rotation to yaw/pitch/roll](https://gist.github.com/ChingT/3830c9c2a7ef8bc327070745bf357410) - The Heade Pose Tracker in Pupil Player exports the head pose to `head_pose_tacker_poses.csv`. The linked function transforms the [head pose rotation vector](https://docs.pupil-labs.com/core/software/pupil-player/#analysis-plugins) to yaw/pitch/roll in degrees. Starting with Pupil Core v3.4, this feature is built into Pupil Player.
- [Post-hoc fixation, saccade, and blink detection](https://github.com/teresa-canasbajo/bdd-driveratt/tree/master/eye_tracking/preprocessing) - Pipeline that takes in the pupil labs subject data and outputs cleaned fixation, saccades and blinks. It also has a surface detection & mapping option.
- [Cognitive workload tool for the Pupil eye tracker](https://github.com/pignoniG/cognitive_analysis_tool) - Processing of eye tracking data, using the Pupil Labs eye tracker, for the measure of cognitive workload. [Associated thesis](https://ntnuopen.ntnu.no/ntnu-xmlui/handle/11250/2617732).
- [CLAHE Scene Video Post-Processing](https://gist.github.com/papr/045c6b6ad2eeedbae8cc2e0c503bb729) - Preview plugin for Pupil Player and application script to apply [CLAHE](https://docs.opencv.org/4.x/d5/daf/tutorial_py_histogram_equalization.html) permanently to the scene video

### Small Examples
- [Visualize reference data from recorded calibrations](https://nbviewer.jupyter.org/gist/papr/ad50c1146d297deef9a1738a4731eb45)
- [Example how to read Pupil-Player-generated reference locations](https://gist.github.com/papr/655cc5f005ca032b0eb602317e89f9ba)

## Demo Videos

- [Pupil Demo Videos](https://www.youtube.com/watch?v=X_BalnBOcpk&list=PLi20Yl1k_57pr6zl9D6JHSrOWyLXxsTQN) - A playlist of community contributed videos.
