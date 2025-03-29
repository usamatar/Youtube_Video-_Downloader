# YouTube Video Downloader

A simple **YouTube Video Downloader** built using **Python (pytube)** and **Tkinter** for folder selection.

## Features
- Download YouTube videos in **MP4 format** with the highest available resolution.
- Select a custom download location using a **file dialog**.
- Simple **command-line input** for ease of use.

## Requirements
Make sure you have Python installed. Then, install the required dependencies:

```bash
pip install pytube
```

For Linux/macOS users, if `tkinter` is missing, install it using:
```bash
sudo apt-get install python3-tk  # Ubuntu/Debian
brew install python-tk           # macOS (Homebrew)
```

## Usage
1. Clone this repository:
```bash
git clone https://github.com/yourusername/youtube-video-downloader.git
cd youtube-video-downloader
```

2. Run the script:
```bash
python youtube.py
```

3. Enter the YouTube **video URL** when prompted.
4. Select a **download folder** from the file dialog.
5. The video will start downloading, and a success message will be displayed when complete.

## Troubleshooting
### 1. HTTP Error 400: Bad Request
- Ensure your **pytube** library is up to date:
  ```bash
  pip install --upgrade pytube
  ```

### 2. Tkinter Not Opening
- Ensure Tkinter is installed (`sudo apt-get install python3-tk` for Linux users).
- Use `root.update()` before opening the file dialog if necessary.

