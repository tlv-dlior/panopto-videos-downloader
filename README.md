# Panopto Videos Downloader

Panopto Vidoes Downloader is a Python script for downloading Technion course videos from Panopto 

# Getting Started

## Prerequisites

[Python 3.7.x](https://www.python.org/downloads/) or newer version should be installed

[Git](https://git-scm.com/downloads) should be installed

## Installation

1. Clone the repo
```bash
$ git clone https://github.com/dlior/panopto-videos-downloader.git
$ cd panopto-videos-downloader
```

2. Use the package manager [pip]() to install required packages
```bash
$ pip install -r requirements.txt
```

## Using Panopto Vidoes Downloader

1. In Google Chrome subscribe to RSS

    ![](Assets/RSS.png)

2. Copy the URL and paste it in the url variable in the script then save file

```python
url = "RSS URL Here"
```

3. Open terminal and run the script:
```bash
$ python panopto_videos_downloader.py
```

## Example

RSS URL for Technion course 094224 - Data Structures and Algorithms (Tutorials)

```python
url = "http://panoptotech.cloud.panopto.eu/Panopto/Podcast/Podcast.ashx?courseid=2b22b19c-f958-4153-9765-a97d00e07ad5&type=mp4"
```
![](Assets/progress_bar.png)

## License
[MIT](https://choosealicense.com/licenses/mit/)


