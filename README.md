# Heart Rate Viewer

The Heart Rate Viewer is a Python application with a graphical user interface (GUI) built using Tkinter and Matplotlib. This tool is designed for visualizing and analyzing heart rate data over time. The application generates synthetic heart rate data based on user input or random values and provides an interactive interface for exploring the data.

## Features

- **Real-time Plotting:** Dynamically visualize heart rate data based on user input, highlighting abnormal rates in "HALTER MODE" for quick identification.

- **Data Reload:** Use the "Load Heart Rate" button to reload synthetic heart rate data, providing a fresh start for analysis.

- **Interactive Data Cursor:** Hover over the plot to view precise time and heart rate values with the Matplotlib data cursor feature.

## Usage

1. Enter a heart rate (bpm) or specific time in the input field.
2. Click "Plot Heart Rate" to visualize the data around the selected point.
3. Use the "Load Heart Rate" button to generate new synthetic data for analysis.

## Installation

To run the Heart Rate Viewer, make sure you have Python installed. Clone the repository and execute the script.

```bash
git clone https://github.com/Ayushomega14/heart-rate-viewer.git
cd heart-rate-viewer
python heart_rate_viewer.py
