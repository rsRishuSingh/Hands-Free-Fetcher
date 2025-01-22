# File Downloader and Organizer

This project is a Python script designed to download images, videos, and PDFs from specified URLs, organize them into appropriate folders, and provide voice feedback for the status of various tasks. The script uses multithreading and multiprocessing to optimize the downloading and organizing processes.

## Features

- **Image Downloader**: Downloads a specified number of images from a given URL.
- **Video Downloader**: Downloads videos from a predefined list of URLs.
- **PDF Downloader**: Downloads PDFs from a predefined list of URLs.
- **File Sorting**: Automatically sorts downloaded files into designated folders (Images, Videos, PDFs).
- **Voice Feedback**: Provides real-time audio updates on the progress of tasks.
- **Error Handling**: Includes error handling to ensure smooth execution.

## Technologies Used

- **Python Libraries**:
  - `requests` for HTTP requests.
  - `os` and `shutil` for file operations.
  - `pyttsx3` for text-to-speech functionality.
  - `speech_recognition` for voice command input.
  - `threading` and `concurrent.futures` for multithreading.

## Prerequisites

Before running the script, ensure the following:

1. Python 3.x is installed on your system.
2. Required Python libraries are installed. Install them using:
   ```bash
   pip install requests pyttsx3 SpeechRecognition
   ```
3. An internet connection is available for downloading files.

## How to Run

1. Clone or download this repository to your local machine.
2. Open a terminal and navigate to the project directory.
3. Run the script using the command:
   ```bash
   python script_name.py
   ```
4. Follow the on-screen instructions and provide voice or text input when prompted.

## Functionality Overview

### 1. **Image Downloader**
Downloads a specified number of images from `https://loremflickr.com` and saves them in a temporary folder named `DeleteME`.

### 2. **Video Downloader**
Downloads videos from predefined URLs and saves them in the `DeleteME` folder.

### 3. **PDF Downloader**
Downloads PDFs from predefined URLs and saves them in the `DeleteME` folder.

### 4. **File Sorting**
Moves downloaded files from `DeleteME` to designated folders (`Image folder`, `Video folder`, `PDF folder`) within a `Sycamore` directory.

### 5. **Voice Feedback**
Provides audio updates for the start and end of each task.

## Folder Structure

- **DeleteME**: Temporary folder for storing downloaded files.
- **Sycamore**: Main folder containing subfolders for organized files:
  - `Image folder`: Stores downloaded images.
  - `Video folder`: Stores downloaded videos.
  - `PDF folder`: Stores downloaded PDFs.

## Future Enhancements

- Add support for user-defined URLs for downloads.
- Implement a graphical user interface (GUI).
- Enhance error handling and logging.

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.

---
