# Profile assets

- `hello.gif`: Custom profile introduction using Armin Eshaghi's existing public GitHub avatar. The animation cycles through “AI/ML Systems Engineer” and “From models to machines” with typing, reading pauses, and deletion. No external animation service is required.
- `hello-still.png`: Static alternative for visitors who prefer reduced motion.
- `microsurgery.gif`: Supplementary Video 1 from [R-M77/Automated_Microsurgery](https://github.com/R-M77/Automated_Microsurgery/blob/main/Supplementary%20Video%201.mp4), presented as a lightweight six-second excerpt at its original playback speed. Only the black letterbox bars are cropped. The tracking overlays come from the source footage.
- `microsurgery-still.png`: Still frame from the same experiment.

Research: [Automation of single cell surgery in real-time using a vision-based control system](https://www.inderscience.com/info/inarticle.php?artid=118413), Armin Eshaghi and James K. Mills, 2021.

## Contact and technology graphics

The `link-*.svg` files are small local contact/navigation labels made for this profile. They do not rely on an external badge service.

The `tech-*.svg` icons are from [Devicon](https://github.com/devicons/devicon), used under its MIT license. See `DEVICON-LICENSE.txt`. Source paths are `icons/<name>/<name>-original.svg`, except Python, which uses `icons/python/python-plain.svg`. Brand names and logos belong to their respective owners.

## Featured project figures

- `microsurgery-sequence.png` pairs the first and last frames of the six-second excerpt above. The timestamps are relative to that clip. The narrow-screen version uses `microsurgery-still.png` to keep the cell and tool tip legible.
- `tensor-traffic.png` plots the baseline and optimized totals from the [MLIR Cost Model Lab example](https://github.com/R-M77/mlir-cost-model-lab/tree/0923500eebea6f912d019515dd39f805b6485904). The command `python -m cost_model --optimize examples/matmul_bias_relu.json` reports 152 bytes read and 96 written before fusion, and 120 read and 64 written after fusion. Bars show the sum of logical reads and writes from zero.
- `jetsoncast-preview.jpg` shows the phone and TV from the [JetsonCast demo poster](https://github.com/R-M77/JetsonCast/blob/b7670309d9d972963afda0f91640bddec4719c20/assets/previews/demo-poster.png). The scene and controls are illustrative. The [device guide](https://github.com/R-M77/JetsonCast/tree/b7670309d9d972963afda0f91640bddec4719c20/devices) records the physical hardware checks.
