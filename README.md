<a href="https://r-m77.github.io/R-M77/?play=banner"><picture><source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/main/assets/hello-still.png"><img src="assets/hello.gif" width="100%" alt="Armin Eshaghi — AI/ML Systems Engineer. From models to machines."></picture></a>

# Embedded vision and ML systems

I build computer vision software for automotive edge processors. I’ve written image-correction libraries in C and tested MobileNet on custom silicon. I’m interested in embedded ML roles where accuracy, latency, and memory use shape what runs on the device.

[Play profile animations](https://r-m77.github.io/R-M77/?play=banner) · [Résumé](https://github.com/R-M77/Resume/blob/main/Resume_Armin_Eshaghi.pdf) · [Publications](https://github.com/R-M77/Resume/blob/main/Publications.md) · [LinkedIn](https://www.linkedin.com/in/armineshaghi)

## Vision-guided microsurgery

For my M.A.Sc. at the University of Toronto, I developed methods to locate cell features in 3D and steer a micromanipulator with visual feedback. Each new microscope frame lets the controller check the tool’s position and correct its motion.

<a href="https://r-m77.github.io/R-M77/?play=control"><picture><source media="(max-width: 550px) and (prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/main/assets/figures/control-loop-compact-still.svg"><source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/main/assets/figures/control-loop-still.svg"><source media="(max-width: 550px)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/main/assets/figures/control-loop-compact.svg"><img src="assets/figures/control-loop.svg" width="640" alt="Microscope footage and feedback loop. The controller tracks position, corrects the tool’s motion, and checks the next frame."></picture></a>

[Watch the 6-second clip](https://r-m77.github.io/R-M77/?play=clip) · [Read my first-author paper](https://www.inderscience.com/info/inarticle.php?artid=118413) · [Browse the experiments](https://github.com/R-M77/Automated_Microsurgery)

## MLIR Cost Model Lab · Saving a tensor round trip

I built a Python cost model to trace where tensor programs move data. In this example, ReLU consumes eight values from a bias addition. Fusing the two operations eliminates a write and a read of those values, cutting **modeled memory traffic by 25.8%** for the same 64 scalar operations.

<a href="https://r-m77.github.io/R-M77/?play=fusion"><picture><source media="(max-width: 550px) and (prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/ffacf42ffdae630c3e8061a1d3ea63cb0231bb8d/assets/figures/tensor-fusion-compact-still.svg"><source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/ffacf42ffdae630c3e8061a1d3ea63cb0231bb8d/assets/figures/tensor-fusion-still.svg"><source media="(max-width: 550px)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/ffacf42ffdae630c3e8061a1d3ea63cb0231bb8d/assets/figures/tensor-fusion-compact.svg"><img src="https://raw.githubusercontent.com/R-M77/R-M77/ffacf42ffdae630c3e8061a1d3ea63cb0231bb8d/assets/figures/tensor-fusion.svg" width="724" alt="Eight float32 values form a 32-byte intermediate tensor. Fusing bias addition and ReLU removes a write and a read, reducing total modeled traffic from 248 to 184 bytes."></picture></a>

[Play the fusion animation](https://r-m77.github.io/R-M77/?play=fusion) · [Run the example](https://github.com/R-M77/mlir-cost-model-lab#run-a-reproducible-example) · [Walk through the byte counts](https://gist.github.com/R-M77/d473a24becf85af5ce83941cb51230c2)

## Synchronized gait capture at Toronto Rehab

At Toronto Rehab (UHN), I synchronized cameras and motion sensors so we could examine the same moment in a person’s stride. I integrated the hardware triggers with the C++ and Python capture software and built an OpenCV pipeline for gait analysis and fall-prediction research.

<a href="https://r-m77.github.io/R-M77/?play=gait"><picture><source media="(max-width: 550px) and (prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/ffacf42ffdae630c3e8061a1d3ea63cb0231bb8d/assets/figures/gait-capture-compact-still.svg"><source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/ffacf42ffdae630c3e8061a1d3ea63cb0231bb8d/assets/figures/gait-capture-still.svg"><source media="(max-width: 550px)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/ffacf42ffdae630c3e8061a1d3ea63cb0231bb8d/assets/figures/gait-capture-compact.svg"><img src="https://raw.githubusercontent.com/R-M77/R-M77/ffacf42ffdae630c3e8061a1d3ea63cb0231bb8d/assets/figures/gait-capture.svg" width="724" alt="Schematic of a walking stride and three aligned timing tracks for camera frames, motion-sensor samples, and a hardware trigger."></picture></a>

[Play the timing illustration](https://r-m77.github.io/R-M77/?play=gait) · [Read about my work at Toronto Rehab](https://github.com/R-M77/Resume/blob/main/Resume_Armin_Eshaghi.pdf)

## JetsonCast for older TVs

My TV had HDMI but no YouTube app, so I turned an 8 GB Jetson Orin Nano into a receiver. VacuumTube handles playback. I built the Linux setup and audio routing, then tested casting from my phone with video and sound over the Jetson’s DisplayPort-to-HDMI connection.

<a href="https://r-m77.github.io/R-M77/?play=jetson"><picture><source media="(max-width: 550px) and (prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/main/assets/figures/jetsoncast-compact-still.svg"><source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/main/assets/figures/jetsoncast-still.svg"><source media="(max-width: 550px)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/eccb87a8998a4218eb37926b20db4af782704e03/assets/figures/jetsoncast-compact.svg"><img src="https://raw.githubusercontent.com/R-M77/R-M77/eccb87a8998a4218eb37926b20db4af782704e03/assets/figures/jetsoncast.svg" width="640" alt="The public JetsonCast demo banner and casting path from the phone through a Jetson Orin Nano to the TV."></picture></a>

[Watch the 27-second demo](https://r-m77.github.io/R-M77/?play=jetson) · [Set up a receiver](https://github.com/R-M77/JetsonCast#quick-start)

### Other engineering work

- [RFID reader integration in C++](https://github.com/R-M77/AMBIENT_video_capture/blob/dev/G_test.cpp) — USB reader discovery, tag inventory, and timestamped CSV logging.
- [OpenClaw scheduling prototype](https://github.com/R-M77/openclaw/tree/feat/main-session-agent-turn) — a TypeScript change that lets a scheduled job reuse the main session’s conversation context.
