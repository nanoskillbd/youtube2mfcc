
# 🎧 YouTube MFCC Visualizer

This project demonstrates how to extract and visualize MFCC (Mel-Frequency Cepstral Coefficients) features from a YouTube video using Python.

## 📌 Features
- Downloads audio from a public YouTube video
- Converts the audio to WAV format using `yt-dlp` and `ffmpeg`
- Extracts MFCC features using `librosa`
- Visualizes the MFCCs using `matplotlib`

## 📂 Files
- `youtube_mfcc_visualizer.ipynb`: Jupyter notebook containing the full workflow

## 🛠 Requirements

Install the required libraries with:

```bash
pip install yt-dlp librosa matplotlib numpy
```

Ensure `ffmpeg` is installed and available in your system PATH.

## 🚀 How to Run

1. Clone this repository or upload the notebook to your own repo.
2. Run the notebook cells in sequence.
3. Update the YouTube URL if you want to use a different video.

## 🔍 What are MFCCs?

MFCCs are features that represent the short-term power spectrum of audio and are widely used in speech and audio recognition tasks.

## 📸 Sample Output

The notebook will produce a time-frequency heatmap of MFCC coefficients.

## 🧑‍💻 Author

Hasan Md. Shahriare  
[hasanshahriare.com](https://hasanshahriare.com)

## 📜 License

This project is for educational use only. Please do not upload copyrighted content.
