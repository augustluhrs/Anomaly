# Anomaly

TD Project for Anomaly Face Siphon

## Special Thanks / Show Team

Madison Wada
Philip Errico
Annette 

## Credits

Thanks to Torin Blankensmith and everyone who made the [TD Mediapipe Plugin](https://github.com/torinmb/mediapipe-touchdesigner)

## License

CC-BY-NC

## Workflow (In Progress)

### Setup

- Open the touch project and make sure Mediapipe is loaded / toxes all work.
  - toxes not in repo, download from above and put the `toxes/` folder in root
- Check MIDI connection
- Make sure phone and computer is on same wifi
- Open phone OBS cam or other NDI Sender, make sure appears in NDI In TOP or as webcam option if using OBS Virtual Camera
- Turn on projector, open output window
- Open Control Window

### Phone Operator

- Can zoom, adjust exposure, etc.
- Orientation of phone shouldn't matter?

### Control UI

*Designed to be used with MIDI controller with knobs for scale, rotation, and scrubbing*

### TODO

- [X] Repo
- [X] Mediapipe setup and stripped
- [X] output window for projector
- [ ] face siphon
  - [ ] center
  - [ ] normalize
  - [X] add xy adjust
  - [X] add scale adjust
  - [X] send to output
- [ ] face tracking
  - [ ] use nose XY as rough modifier for XY
  - [ ] center calibration offset?
- [ ] control screen
  - [ ] cache select
  - [ ] XY adjust
  - [ ] scale adjust
  - [ ] rotation adjust knob
  - [ ] horiz flip
  - [ ] debug face out

pomo 1: repo init
pomo 2: project set up and todo
pomo 3: face siphon centered
pomo 4: simple control adjust
pomo 5: cache
pomo 6: switch reactive to music?
