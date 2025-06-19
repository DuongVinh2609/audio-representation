
# 🎵 Audio Signal Representation with Python

This project demonstrates how to load, analyze, and visualize audio signals using Python libraries such as `librosa`, `matplotlib`, and `scipy`. The goal is to compare and understand audio characteristics through various representations including:

- Time-domain waveform
- Frequency-domain (via FFT)
- Time-frequency spectrogram (STFT)

Two sample audio files are analyzed in this project:
- `guitarTune.wav` – a short guitar tune
- `babyCry.mp3` – a baby crying sound

---

## 📂 Project Structure

```
audiorepresentation.py     # Main Python script for audio analysis
guitarTune.wav             # Sample audio (user-provided)
babyCry.mp3                # Sample audio (user-provided)
```

---

## 🔧 Requirements

Install the required Python libraries:

```bash
pip install librosa matplotlib scipy
```

> Optional (for interactive playback in Jupyter):
```bash
pip install ipython
```

---

## 🚀 How to Run

You can run the script in Google Colab or any Python environment that supports audio processing.

### Option 1: Run locally

1. Place `guitarTune.wav` and `babyCry.mp3` in the same directory as the script.
2. Run the script:

```bash
python audiorepresentation.py
```

### Option 2: Use in Jupyter/Colab

This project was originally written in a Jupyter Notebook and can be opened via [Google Colab](https://colab.research.google.com/):

```python
# Click the link in the script header or upload the .ipynb version
```

---

## 📊 Output Visualization

The script provides:

1. **Waveforms** in the time domain for both signals.
2. **FFT plots** to visualize frequency components.
3. **Spectrograms** showing how frequencies change over time.

These visualizations help understand how different sounds (like music vs. baby cry) vary in structure and frequency.

---

## 🔍 Example Visuals

| Waveform (Time Domain) | FFT (Frequency Domain) | Spectrogram (Time-Frequency) |
|------------------------|------------------------|------------------------------|
| *(Add example_waveform.png)* | *(Add example_fft.png)* | *(Add example_spec.png)* |

> 📌 *Note: Add example screenshots to your repo if needed.*

---

## 🧠 Future Improvements

- Wrap the script into reusable functions or a Python class.
- Add Mel-spectrogram or MFCC features.
- Add GUI or interactive sliders using `streamlit` or `gradio`.
- Extend with audio classification or detection tasks.

---

## 📝 License

This project is open-source and provided for educational purposes. Feel free to fork or modify it.

---

## 🙋‍♂️ Author

This is a personal project developed during free time for learning and experimenting with digital audio signal processing.

> Feedback and contributions are welcome!
