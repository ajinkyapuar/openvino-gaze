# OpenVINO Gaze Pipeline

# Downloading Models

- `omz_downloader --name face-detection-adas-0001`
- `omz_downloader --name landmarks-regression-retail-0009`
- `omz_downloader --name head-pose-estimation-adas-0001`
- `omz_downloader --name gaze-estimation-adas-0002`

# Run

- `python src/main.py -i cam -all_dev GPU --show_output True -b 1`
- `python src/main.py -i video -if data/demo.mp4 -all_dev GPU --show_output True`