# MPHY0058 Group Coursework : Heart rate estimation via Signal and Image Processing

## Project Overview
This repository contains the Python code, data, generated figures, and final report for the MPHY0058 group coursework. The aim of this project is to estimate human heart rate (in BPM) from two different photoplethysmography (PPG) data sources:
- **Problem 1:** Optical sensor data (`heart_beat_signal.csv`) analysed using band-pass filtering, Fast Fourier Transform (FFT), and peak detection, along with sensitivity analyses.
- **Problem 2:** Finger video recording (`video_of_finger.MOV`) processed with OpenCV to extract mean grayscale intensity over time, followed by filtering and FFT analysis.

## Repository Structure
- `Combined_Problem1&2.ipynb` – Main Jupyter Notebook containing the complete workflow for both Problem 1 and Problem 2, including the `save_fig()` function for exporting figures.
- `Problem1.ipynb` & `Problem2.ipynb` – Individual development notebooks for each problem.
- `data/` – Contains the optical sensor CSV file (`heart_beat_signal.csv`) and the finger video (`video_of_finger.MOV`).
- `figures/` – Stores all generated plots saved at 300 DPI in PNG format.
- `report.docx` – Group coursework report.

## Requirements
To run the notebook, Python 3 and the following libraries are required:
- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `opencv-python` (`cv2`)

You can install the required packages using pip:
```bash
pip install numpy pandas matplotlib scipy opencv-python
```

## How to Run
1. Clone this repository to your local machine.
2. Make sure `heart_beat_signal.csv` and `video_of_finger.MOV` are placed inside the `data/` folder.
3. Open `Combined_Problem1&2.ipynb` in VS Code or Jupyter Notebook.
4. Click **Run All** to execute the analysis and automatically save all 7 figures into the `figures/` folder.

## Group Members
- [Jaxintas Lyu]
- [Jingqi Du]
- [Wenqing Li]
- [Nicky Zhou]