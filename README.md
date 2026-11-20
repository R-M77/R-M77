# Embedded vision and ML systems

I build computer vision software for automotive edge processors. I’ve written image-correction libraries in C and tested MobileNet on custom silicon for inference accuracy and latency.

[Résumé](https://github.com/R-M77/Resume/blob/main/Resume_Armin_Eshaghi.pdf) · [Publications](https://github.com/R-M77/Resume/blob/main/Publications.md) · [LinkedIn](https://www.linkedin.com/in/armineshaghi)

## Vision-guided microsurgery

For my M.A.Sc. at the University of Toronto, I developed 3D feature tracking and a feedback controller that steers a micromanipulator using live microscope images. **Follow the green box** to see the tool line up with the target and move toward it.

<a href="https://github.com/R-M77/R-M77/blob/main/assets/microsurgery.gif"><picture><source media="(max-width: 550px)" srcset="https://raw.githubusercontent.com/R-M77/R-M77/main/assets/microsurgery-still.png"><img src="assets/microsurgery-sequence.png" width="680" alt="Microscope tracking overlay. The green box marks the tool tip on the right as it approaches the cell on the left."></picture></a>

[Watch the 6-second clip](https://github.com/R-M77/R-M77/blob/main/assets/microsurgery.gif) · [Read my first-author paper](https://www.inderscience.com/info/inarticle.php?artid=118413) · [Browse the experiments](https://github.com/R-M77/Automated_Microsurgery)

## Tensor fusion in MLIR Cost Model Lab

I built a Python tool that estimates how much data a tensor program reads and writes. In one example, fusing bias addition with ReLU saves **one 32-byte write and one 32-byte read**. Both plans still require 64 scalar operations.

<a href="https://github.com/R-M77/mlir-cost-model-lab#run-a-reproducible-example"><img src="assets/tensor-traffic.png" width="680" alt="Estimated logical memory traffic falls from 248 bytes for separate operations to 184 bytes after fusion."></a>

[Run the fusion example](https://github.com/R-M77/mlir-cost-model-lab#run-a-reproducible-example) · [Inspect the Python estimator](https://github.com/R-M77/mlir-cost-model-lab/blob/main/src/cost_model/estimator.py)

## JetsonCast for older TVs

My TV had HDMI but no YouTube app. I turned an **8 GB Jetson Orin Nano** into a casting receiver using VacuumTube for playback. I built the Linux setup and audio routing, then tested casting from my phone with fullscreen video and sound on the TV.

<a href="https://github.com/R-M77/JetsonCast/blob/main/assets/previews/demo-landscape.mp4"><img src="assets/jetsoncast-preview.jpg" width="520" alt="Illustrated JetsonCast demo with the same coastal video on a phone and a TV. The phone controls playback."></a>

[Watch the 27-second demo](https://github.com/R-M77/JetsonCast/blob/main/assets/previews/demo-landscape.mp4) · [Set up a receiver](https://github.com/R-M77/JetsonCast#quick-start)

### Other engineering work

- [RFID reader integration in C++](https://github.com/R-M77/AMBIENT_video_capture/blob/dev/G_test.cpp) — USB reader discovery, tag inventory, and timestamped CSV logging.
- [OpenClaw scheduling prototype](https://github.com/R-M77/openclaw/tree/feat/main-session-agent-turn) — a TypeScript change that lets a scheduled job reuse the main session’s conversation context.
