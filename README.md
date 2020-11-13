# pupil-community

This repository is a `README` only repository for community contributed projects, forks, plugins, scripts, and videos using [Pupil](https://github.com/pupil-labs/pupil) - open source eye tracking platform.

## Contributing
Want to add your project, fork, plugin, or script to this list? Fork this repo and make a [Pull Request](https://github.com/pupil-labs/pupil-community/pulls) with a link and short description in the README file.

Want to add your demo video to this list? Make an [issue](https://github.com/pupil-labs/pupil-community/issues) with the Youtube link and the maintainers will add the video to [this Youtube playlist](https://www.youtube.com/watch?v=X_BalnBOcpk&list=PLi20Yl1k_57pr6zl9D6JHSrOWyLXxsTQN).

## Projects & Forks
- [Pupil Video Backend](https://github.com/Lifestohack/pupil-video-backend) - Streams Video from another computer through the network to your computer where pupil capture software is running.
- [Pupil Labs Motion Capture Trigger](https://github.com/N-M-T/Pupil-Labs-Mocap-Trigger) - Use a low-cost Arduino microcontroller to synchronise motion capture systems (e.g. Vicon/Qualisys) with the Pupil Core Mobile eye tracker.
- [Plugin to Perceive the Object in Focus](https://github.com/jesseweisberg/pupil) - Real-time object-detection plugin that integrates eye-tracking (fixation data) to identify which object the user is currently fixated upon. An example of its potential is shown in controlling grasps of a robotic prosthetic hand. Part of the [Therabotics Project](https://www.jesseweisberg.com/therabotics/)
- [PolyMouse](https://github.com/trishume/PolyMouse) - PolyMouse is a fusion of gaze tracking and head tracking to achieve hands-free pointing. It does this by using eye gaze to quickly determine an imprecise area of interest and then uses small head movements to refine the position of the cursor onto a small target.
- [Asistiva](https://github.com/hookdump/asistiva) - a set of tools for creating amazing web apps optimized to be used through different input methods (i.e. including eye-tracking, head-tracking, button-less mouse, adapted switches, etc).
- [Focal](http://stewartgreenhill.com/articles/focal/) - Focal is an experimental eye-tracking musical expression controller which allows hands-free control over audio effects and synthesis parameters during performance. A see-through head-mounted display projects virtual dials and switches into the visual field.
- [Graph viz eye tracker](https://github.com/Saftophobia/graph-viz-eye-tracker) - Creating a gaze-aided graph navigating application using Unity3D and Pupil-lab.
- [Optical Dimension Spatial Thinking - ODST](https://github.com/Ruzzy77/ODST) - Gaze controlled interface using gaze data and voice recognition.
- [PuRe Detector](https://github.com/mattem86/pupil/tree/PuRe-Detector) - Included the PuRe Detector from Santini et al. into the Pupil Labs GUI. It is a 2D only detector (for now) and can only be used in non-commercial applications. Thiago Santini, Wolfgang Fuhl, Enkelejda Kasneci, PuRe: Robust pupil detection for real-time pervasive eye tracking, Computer Vision and Image Understanding, 2018, ISSN 1077-3142, https://doi.org/10.1016/j.cviu.2018.02.002. Based on https://atreus.informatik.uni-tuebingen.de/santini/EyeRecToo/tree/master/EyeRecToo
- [PupilCamC++](https://github.com/themrx/PupilCapture) - Interface for capture of Pupil labs cameras with C++, primarily for windows
- [Pupil-lib Trial/Event Extraction Library](https://github.com/gmierz/pupil-lib-python) - A flexible tool for conducting high precision event based research analysis with Pupil Labs eye trackers. See [here](https://github.com/gmierz/pupil-lib-python/blob/master/README.md#running-a-compatible-experiment) for how to run an experiment that produces data compatible for this library. A [Matlab version](https://github.com/gmierz/pupil-lib) is also available.
- [Mobile Gaze Mapping](https://github.com/jeffmacinnes/mobileGazeMapping) - Automatic gaze mapping between world camera and a fixed reference stimulus. This tool provides automatic detection of a 2D target stimulus in a mobile eye-tracking recording, and translates recorded gaze data from the world camera to the fixed coordinate system of the stimulus itself. 
- [JupilLabs](https://github.com/auejin/JupilLabs) - A Processing(Java) binding for extracting data from pupil-labs with jeromq and msgpack-java

## Plugins

- [Gaze-controlled VLC Player - gvlc](https://github.com/MPIK-COMMS/gcvlc) - Gaze-controlled VLC player using Pupil Capture.
- [Pupil Labs usybus Controller](https://github.com/Lahorde/pupil-labs-usybus-controller) - This plugin exports pupillabs eye tracking gaze to [Ivybus](http://www.eei.cena.fr/products/ivy/).
- [Pupil progs](https://github.com/SGBon/pupil-progs) - Python helper scripts used with Pupil (post-hoc and real-time).
- [@cpicanco's Pupil Player Plugins](https://github.com/cpicanco/player_plugins) - A collection of visualization and analysis plugins for Pupil Player.
- [@cpicanco's Pupil Capture Plugins](https://github.com/cpicanco/capture_plugins) - A collection of plugins for Pupil Capture.
- [Online Task Proxy](https://gist.github.com/papr/0eaba2bc70755ffb1ad05385a3458a07) - Example plugin that shows how to use the `Task_Proxy` class in Pupil Capture
- [Unix Time Sync](https://gist.github.com/papr/87c4ab1f3b533510c4585fee6c8dd430) - Example plugin that shows how to synchronize the Pupil clock to Unix time
- [Depth Frame Accessor](https://gist.github.com/papr/0f13943e2aebd768ab6b1508d466caae) - Example plugin that shows how to access the 16 bit depth data of Realsense frames in Capture
- [TaskLib Example](https://gist.github.com/ckbaumann/c21501ce28c4ba3cdd7bdf19fabb6d09) - Example plugin that demonstrates basic `task_lib` usage.
- [Pupil 2D Detection Preview](https://github.com/Christopher22/pupil_preview) - Plugin which shows a scrollable gallery of eye images with 2D pupil detection after a recording stops. Its purpose is to get a brief visual insight of how good the detection will be, when the online detector was disabled due to perfomance or stability reasons. The eye images are saved with a fixed time interval in a subdirectory of the recording. It also shows the usage of changing the detection properties and accessing the GPOOL in a plugin. The frame publisher has to be enabled during recording.
- [RealSense D400 Source v1.22](https://gist.github.com/pfaion/080ef0d5bc3c556dd0c3cccf93ac2d11) - A port of the old realsense2 plugin (for RealSense D400 series cameras) to work with the new video source framework in Pupil Capture v1.22.
- [Ximea Camera Plugin](https://github.com/vdutell/PupilXimea) - A plugin to preview and record frames from Ximea Cameras using XiAPI.
- [Dual-monocular 2D and 3D Gazers](https://gist.github.com/papr/5e1f0fc9ef464691588b3f3e0e95f350) - 2D and 3D gaze mapping plugins that map all pupil data monocularly. Recommended if when investigating strabismus or similar conditions. Requires Pupil v2.2 or higher.

## Scripts
- [OptiTrack and Pupil Labs Python Recorder](https://github.com/mdfeist/OptiTrack-and-Pupil-Labs-Python-Recorder) - A simple python script that records data from Pupil Labs and OptiTrack.
- [Offline Gaze Mapping Tools for Pupil Labs Glasses](https://github.com/jeffmacinnes/pl_gazeMapping_offline) - Offline Gaze Mapping Tools for Pupil.
- [Eye Tracking Research Data Analysis ](https://github.com/qalhata/Eye-Tracking-Research-Fixation-EDA-PupilLabs-Data-) - Python pupillometry analysis scripts to analyize pupil_data. 
- [Lab Matlab Control](https://github.com/TheGoldLab/Lab-Matlab-Control/tree/62d56585ef2fda3c17045dfcdc69e159eb317a38) - Custom utilities for experimental control.
- [Pupil Pascal Client](https://github.com/cpicanco/pupil-fpc) - Free Pascal requester and subscriber clients for Pupil.
- [Pupil MatLab Client](https://github.com/matiarj/pupil-helpers/tree/matlabAddV2/pupil_remote/Matlab_Python) - MatLab subscriber client for Pupil.
- [Pupil Middleman](https://github.com/mtaung/pupil_middleman#pupil-middleman) - A middleman client written in Python. This client can be used to interface with Pupil Capture and other sytems and languages that do not natively support ZeroMQ. 
- [Surface OSC Bridge](https://github.com/papr/pupil-helpers/tree/oscbridge/pupil_remote/OSC_Python) - Redirects
surface data using the [`OSC` protocol](http://opensoundcontrol.org/introduction-osc).
- [extract_diameter.py](https://gist.github.com/papr/743784a4510a95d6f462970bd1c23972) - Extract 2d and 3d (if available) pupil diameters for a set of given recordings
- [batchExportPupilLabs](https://github.com/tombullock/batchExportPupilLabs) - Batch exports prercorded data as csv for a set of given recordings
- [Network Topic Monitor](https://nbviewer.jupyter.org/gist/pfaion/115e13e822b308f0896b59bc7971d676) - A very simple network topic monitor. Shows notification count for every topic and how long ago the last notification was received.
- [Head pose rotation to yaw/pitch/roll](https://gist.github.com/ChingT/3830c9c2a7ef8bc327070745bf357410) - The Heade Pose Tracker in Pupil Player exports the head pose to `head_pose_tacker_poses.csv`. The linked function transforms the [head pose rotation vector](https://docs.pupil-labs.com/core/software/pupil-player/#analysis-plugins) to yaw/pitch/roll in degrees.
- [Post-hoc fixation, saccade, and blink detection](https://github.com/teresa-canasbajo/bdd-driveratt/tree/master/eye_tracking/preprocessing) - Pipeline that takes in the pupil labs subject data and outputs cleaned fixation, saccades and blinks. It also has a surface detection & mapping option.

## Demo Videos

- [Pupil Demo Videos](https://www.youtube.com/watch?v=X_BalnBOcpk&list=PLi20Yl1k_57pr6zl9D6JHSrOWyLXxsTQN) - A playlist of community contributed videos.
