# Adaptive FEC Audio Demo

A simple Python demo of Adaptive Forward Error Correction (FEC) for audio streaming, based on French and Claypool (2001).

The notebook demonstrates FEC packet construction, network packet loss, audio recovery, and fixed vs. adaptive repair depth.

## Files

- `01_adaptive_fec_demo.ipynb` — main notebook
- `assets/demo_audio.flac` — audio sample
- `assets/paper_figures/` — figures from the reference paper

## How to Run

Install the required packages:

```bash
pip install numpy scipy matplotlib soundfile ipython jupyterlab
```

Launch JupyterLab:

```bash
jupyter lab
```

Open `01_adaptive_fec_demo.ipynb` and run all cells.

## References

**Paper:** French, K., and Claypool, M. (2001). *Repair of Streaming Multimedia with Adaptive Forward Error Correction*. 

**Audio:** [Voice-Zero](https://github.com/OwenTyme/voice-zero) — original filename: `jodi_krangle.flac`.

Figures 1–3 are reproduced from the reference paper.