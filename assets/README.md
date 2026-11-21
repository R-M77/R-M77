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
| `figures/tensor-fusion*.svg` | The [Python example](https://github.com/R-M77/mlir-cost-model-lab/tree/0923500eebea6f912d019515dd39f805b6485904) reports 152 bytes read and 96 written before fusion, and 120 read and 64 written after fusion. The totals cover the full example graph. |
| `figures/jetsoncast.svg` | Embeds the [public JetsonCast banner](https://github.com/R-M77/JetsonCast/blob/73675d73422fdc0a0f52283cd4232fd86f1a11a8/assets/previews/banner.gif) on a repeating 4.8-second cycle above the animated signal path. Reduced motion uses the project's banner poster. |
