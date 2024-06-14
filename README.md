# Anomaly

TD Project for Anomaly Face Siphon

## Special Thanks / Show Team

Madison Wada
Philip Errico
Annette Buesaquillo

## Credits

Thanks to Torin Blankensmith and everyone who made the [TD Mediapipe Plugin](https://github.com/torinmb/mediapipe-touchdesigner)

[Teardrop Anim](https://www.shutterstock.com/video/clip-1103692871-crying-tears-animation-green-screen-background)

[Welling Anim](https://www.youtube.com/watch?v=DsRQaIh9JOM)

## License

CC-BY-NC

## Post Mortem So I Don't Forget

- run through would have been good
- rotation issue with pre-shrunk, needed reset button as panic button
- projector preset would've helped a lot
- beat faces should've had a bit more fade in since it was very obvious what was the feedback and what was pre-recorded
- the live adjustment was a good backup, but would've been nice having auto-sizing and auto-position
- trickle could've been a bit more uniform, would've been nice to have preset flow values so the stages would've been easier to land timing-wise. lots of delay between dial and output, so hard to finetune live.
- projector directly centered on her face would've been a lot better. too much angle. way to adjust her position live?

## Workflow (In Progress aka, never finished)

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
