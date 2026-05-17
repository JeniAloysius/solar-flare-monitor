# Solar Flare Impact Forecaster

A real-time solar flare monitoring and visualization system that fetches live GOES X-ray flux data from NOAA and displays solar flare intensity trends across multiple energy bands.

The project processes real-time space weather data and visualizes X-ray flux variations to help analyze ongoing solar activity and flare behavior.

---

## Features

- Real-time solar flare data collection from NOAA SWPC
- Live visualization of X-ray flux intensity
- Multi-band solar activity tracking
- Time-series plotting using Matplotlib
- Automated data parsing and preprocessing using Pandas

---

## Technologies Used

- Python
- Pandas
- Requests
- Matplotlib
- NOAA SWPC API

---

## How It Works

1. Fetches live GOES X-ray flux data from NOAA
2. Converts JSON response into a structured dataframe
3. Processes timestamps for visualization
4. Separates solar activity by energy bands
5. Plots real-time solar flare intensity trends

---

## Data Source

NOAA Space Weather Prediction Center (SWPC)

https://services.swpc.noaa.gov/json/goes/primary/xrays-1-day.json

---

## Run Locally

```bash
git clone https://github.com/yourusername/solar-flare-impact-forecaster
cd solar-flare-impact-forecaster
pip install pandas matplotlib requests
python main.py
