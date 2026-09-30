<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="assets/hello-still.png">
  <img src="assets/hello.gif" alt="Armin Eshaghi — AI/ML Systems Engineer. From models to machines." width="100%">
</picture>

<p>
  <a href="https://www.linkedin.com/in/armineshaghi"><img src="assets/link-linkedin.svg" alt="Connect on LinkedIn" height="30" width="112"></a>
  <a href="https://github.com/R-M77"><img src="assets/link-github.svg" alt="Follow on GitHub" height="30" width="105"></a>
  <a href="https://github.com/R-M77/Resume/blob/main/Resume_Armin_Eshaghi.pdf"><img src="assets/link-resume.svg" alt="Read my résumé" height="30" width="111"></a>
  <a href="https://github.com/R-M77/Resume/blob/main/Publications.md"><img src="assets/link-publications.svg" alt="Read my publications" height="30" width="147"></a>
</p>

Hi, I'm Armin. My background is in **embedded systems, computer vision, and robotics**, from ASIC validation and hardware/software integration to guiding robots with visual feedback.

I'm building on that experience through **ML systems, inference, compilers, and edge AI**. This profile brings together my research, small tools, and experiments as I work across those areas.

## Tools & technical background

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/tech-python.svg" alt="Python" width="22" height="22">&nbsp;
      <img src="assets/tech-cplusplus.svg" alt="C++" width="22" height="22">&nbsp;
      <strong>Languages</strong><br>
      Python · C · C++ · CUDA
    </td>
    <td width="50%" valign="top">
      <img src="assets/tech-pytorch.svg" alt="PyTorch" width="22" height="22">&nbsp;
      <img src="assets/tech-tensorflow.svg" alt="TensorFlow" width="22" height="22">&nbsp;
      <img src="assets/tech-opencv.svg" alt="OpenCV" width="22" height="22"><br>
      <strong>ML &amp; computer vision</strong><br>
      PyTorch · TensorFlow / Keras<br>OpenCV · scikit-learn
    </td>
  </tr>
  <tr>
    <td valign="top">
      <img src="assets/tech-linux.svg" alt="Linux" width="22" height="22">&nbsp;
      <img src="assets/tech-docker.svg" alt="Docker" width="22" height="22">&nbsp;
      <strong>Systems &amp; tooling</strong><br>
      Linux · Docker · Git
    </td>
    <td valign="top">
      <img src="assets/tech-arduino.svg" alt="Arduino" width="22" height="22">&nbsp;
      <strong>Hardware &amp; control</strong><br>
      Embedded systems · MATLAB · Arduino
    </td>
  </tr>
</table>

## 🔬 Vision-guided microsurgery

During my **M.A.Sc. at the University of Toronto**, I worked on automating single-cell surgery with real-time 3D visual feedback. The footage below is from that research: microscope images are used to track a cell and guide the micromanipulators.

<a href="https://github.com/R-M77/Automated_Microsurgery">
  <picture>
    <source media="(prefers-reduced-motion: reduce)" srcset="assets/microsurgery-still.png">
    <img src="assets/microsurgery.gif" alt="Real microscope footage from my single-cell surgery research, showing the cell, micromanipulators, and visual-tracking overlays" width="100%">
  </picture>
</a>

<sub>Actual experiment · Excerpt from Supplementary Video 1 · Computer vision + robot control</sub>

I developed image-processing methods to locate features in microscope images and a vision-based controller to guide the tools toward the target. The work brought together **3D image segmentation, motion tracking, and closed-loop control**. The repository contains the supplementary videos and images from these experiments.

**[Watch the experiments →](https://github.com/R-M77/Automated_Microsurgery)** · [Read the paper](https://www.inderscience.com/info/inarticle.php?artid=118413) · [Thesis & publications](https://github.com/R-M77/Resume/blob/main/Publications.md)

## 🛠 Projects & experiments

### [Context-aware scheduled jobs](https://github.com/R-M77/openclaw/tree/feat/main-session-agent-turn)

**Scheduler extension · TypeScript · Tests**

I implemented an OpenClaw cron extension for **context-aware scheduled jobs**. The patch lets message-based agentTurn payloads **reuse the main session’s context** through the existing system-event path.

I added CLI and service validation, updated scheduling tests, and tool documentation for the new dispatch path.

[View patch →](https://github.com/R-M77/openclaw/tree/feat/main-session-agent-turn) · [Proposal](https://github.com/openclaw/openclaw/pull/31827)

### [RFID reader integration](https://github.com/R-M77/AMBIENT_video_capture/tree/dev)

**Hardware prototype · C++ · FEIG RFID SDK**

I built a C++ reader-integration prototype that discovers a USB RFID reader, inventories tags, and collects unique identifiers. **Timestamped CSV output** turns reader scans into **structured records for downstream analysis**.

My changes connect the FEIG RFID SDK to the reader experiment and scanner tests.

[Explore the dev branch →](https://github.com/R-M77/AMBIENT_video_capture/tree/dev) · [Reader prototype](https://github.com/R-M77/AMBIENT_video_capture/blob/dev/G_test.cpp)

### [On-device flower classification](https://github.com/R-M77/TFL_Classify)

**Android model integration · Kotlin · TensorFlow Lite**

I integrated a TensorFlow Lite model into an Android camera-classification app, converting **camera frames into model inputs** and **displaying the top prediction**.

I added **GPU-delegate selection with a four-thread CPU fallback**, alongside model binding and Android build updates.

[Explore my changes →](https://github.com/R-M77/TFL_Classify/compare/f52727f3bfb0854bab352fef27b0f772e9cd2929...d79431169dcbb1ecc35166cc47b77f3f72aa6dee) · [Repository](https://github.com/R-M77/TFL_Classify)

## What I'm working toward

| Inference & deployment | Compilers & hardware |
| :--- | :--- |
| How precision, latency, and memory use affect model execution and deployment | How models are represented, translated, and run on different hardware targets |
| **Robotics & vision** | **Edge AI** |
| Perception, visual feedback, and control in physical systems | Useful models on smaller devices, with quantization and runtime evaluation |

---

**Find me:** [LinkedIn](https://www.linkedin.com/in/armineshaghi) · [GitHub](https://github.com/R-M77) · [All repositories](https://github.com/R-M77?tab=repositories)
