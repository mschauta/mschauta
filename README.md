# Dr. Schauta Marcell

**Independent experimental research in artificial intelligence and machine learning.**

My research interests span computer vision, computational imaging, speech synthesis, including parameter-driven text-to-speech (parametric TTS), and related machine-learning systems.

I am interested in experiments that make methods, assumptions and limitations explicit, with code and supporting evidence published where available.

## Published projects

- **[RGB Mesh Resampling](https://github.com/mschauta/rgb-mesh-resampling)** — Experimental image reconstruction and resampling using a continuous RGB mesh built from pixel-centre samples, with documented methods and a runnable reference implementation.
- **[Frame Blur Detection](https://github.com/mschauta/frame-blur-detection)** — Experiments in video-frame blur detection comparing RGB, grayscale and mesh-derived edge-residual inputs, with documented evaluation and inference code.
- **[Frame Blur Detection — Update 1](https://github.com/mschauta/frame-blur-detection-update-1)** — Expanded signed edge fingerprint-based blur detection using ConvNeXt-Base, with fast inference, spatial cell maps and evaluation across 5.01 million video frames.
- **[Frame Blur Detection — Update 2](https://github.com/mschauta/frame-blur-detection-update-2)** — ConvNeXt-Base blur detector retrained on Update 1's cell maps over 4.85 million frames, giving a continuous blur-mass score and spatial cell maps, with an experiment showing how the coded frame type (I/P/B) changes blur scores.
- **[Frame Blur Detection — Update 3](https://github.com/mschauta/frame-blur-detection-update-3)** — ConvNeXt-Small blur detector trained on Update 1's frames and a continuous 0–30 px photo ladder coded in x264, x265 and AV1, adding a px scale calibrated on photos, with an evaluation showing the frame-type gap gone on photo clips while scores on film still depend on the encode.

## Ongoing work

I am also working on parameter-driven text-to-speech (parametric TTS). This work is in progress and has not yet been published.

Additional projects will be linked here as they become public.
