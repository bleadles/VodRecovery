# Welcome to VodRecovery

This is a Fork of [VodRecovery](https://github.com/Shishkebaboo/VodRecovery) which can be used to recover and download Twitch Vods, Highlights and Clips, containing some adjustments and improvements.

## Installation and Setup

1. Download and install [Python](https://www.python.org/downloads/) and when installing ensure to check the box that says "Add Python to environment variables"
2. Download and install [FFmpeg](https://ffmpeg.org/download.html#get-packages)
3. Download this repository with: `git clone https://github.com/MacielG1/VodRecovery` or by clicking the green "Code" button and selecting "Download ZIP"
4. Navigate inside the downloaded folder
5. Install the requirements by running the `install_dependencies.py` file or the command `pip install -r requirements.txt`
6. Run the program by running the `vod_recovery.py` file or the command `python vod_recovery.py`

## Core Features

- Video Recovery: Find VODs using the listed websites or by manually inputting the values.
- Clip Recovery: Recover clips manually or via mentioned websites.
- Video Format: Recovered VODs and Highlights can be downloaded in various formats such as MP4, MKV, AVI, MOV and TS.
- Random Clip Recovery: Retrieve a set of random clips (5 clips per iteration).
- Download Highlights and VODs: Retrieve highlights and VODs using a direct Twitch URL.
- Multiple Formats: Recovered M3U8 links are available in various formats, including - Chunked (Source Quality), 1080p60, 1080p30, 720p60, 720p30, 480p60, 480p30.
- Platform Compatibility: VodRecovery is compatible with popular platforms such as [TwitchTracker](https://twitchtracker.com/), [Sullygnome](https://sullygnome.com/), and [Streamscharts](https://streamscharts.com/) and also direct Twitch links.
- Bulk Video Recovery: Recovers multiple VODs using CSV files from [Sullygnome](https://sullygnome.com/).
- Bulk Clip Recovery: Easily finds multiple clips using CSV files from [Sullygnome](https://sullygnome.com/).
- Unmute VODs: Unmute M3U8 files so that they can be played in media players.

## Usage

This is the interactive menu:

```
1) VOD Recovery
2) Clip Recovery
3) Download VOD (default .mp4)
4) Unmute & Check M3U8 Availability
5) Set Default Video Format
6) Set Download Directory
7) Help
8) Exit
```

## Notes

- Original Repo: [VodRecovery](https://github.com/Shishkebaboo/VodRecovery) by Shishkebaboo
- Ensure your Video requests comply with [Twitch's Video Retention Policy](https://help.twitch.tv/s/article/video-on-demand).

## Latest Release

https://github.com/MacielG1/VodRecovery/releases/latest
