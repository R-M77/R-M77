# Profile assets

- `hello.gif`: Custom profile introduction using Armin Eshaghi's existing public GitHub avatar. The animation cycles through “AI/ML Systems Engineer” and “From models to machines” with typing, reading pauses, and deletion. No external animation service is required.
- `hello-still.png`: Static alternative for visitors who prefer reduced motion.
- `microsurgery.gif`: Supplementary Video 1 from [R-M77/Automated_Microsurgery](https://github.com/R-M77/Automated_Microsurgery/blob/main/Supplementary%20Video%201.mp4), presented as a lightweight six-second excerpt at its original playback speed. Only the black letterbox bars are cropped. The tracking overlays come from the source footage.
- `microsurgery-still.png`: Still frame from the same experiment.

Research: [Automation of single cell surgery in real-time using a vision-based control system](https://www.inderscience.com/info/inarticle.php?artid=118413), Armin Eshaghi and James K. Mills, 2021.

## Contact and technology graphics

The `link-*.svg` files are small local contact/navigation labels made for this profile. They do not rely on an external badge service.

The `tech-*.svg` icons are from [Devicon](https://github.com/devicons/devicon), used under its MIT license. See `DEVICON-LICENSE.txt`. Source paths are `icons/<name>/<name>-original.svg`, except Python, which uses `icons/python/python-plain.svg`. Brand names and logos belong to their respective owners.

## Animated project figures

The designs use graphite neutrals and the green from the profile avatar. A darker green keeps labels readable in light mode. The README selects a static SVG companion when reduced motion is enabled. Compact layouts use the same evidence as their desktop versions.

| Figure | Source and meaning |
| --- | --- |
| `figures/control-loop*.svg` | The microscope filmstrip uses the 36 frames and frame durations of `microsurgery.gif`. After the excerpt, it holds on the final frame. The arrows summarize position tracking and feedback. |
| `figures/tensor-fusion*.svg` | The isometric 2 × 4 tile represents the eight float32 values between bias addition and ReLU in the [example graph](https://github.com/R-M77/mlir-cost-model-lab/blob/0923500eebea6f912d019515dd39f805b6485904/examples/matmul_bias_relu.json). Amber traces show a 32-byte write and read. Green marks the fused path. Equal-scale bars show 248 and 184 logical bytes for the entire graph. |
| `figures/gait-capture*.svg` | Generated from the [public Python model and timing example](https://github.com/R-M77/gait-capture-demo). Each camera pose and plotted knee angle comes from one synthetic stride. The repo documents the gait landmarks and tests. |
| `figures/jetsoncast.svg` | Plays the frames of the [public JetsonCast banner](https://github.com/R-M77/JetsonCast/blob/73675d73422fdc0a0f52283cd4232fd86f1a11a8/assets/previews/banner.gif) on an SVG timeline that repeats every 4.8 seconds. The artwork and step labels advance together above the signal path. Reduced motion uses the project's banner poster. |
