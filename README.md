# yt-tools

A command line tool to get all kind of information about a youtube video.

## Acknowledgements

This project is based on the `yt` tool from [fabric](https://github.com/danielmiessler/fabric) by Daniel Miessler.

## Installation

1. Install pipx:

macOS:

    brew install pipx

Linux:

    sudo apt install pipx


2. Install yt-tools:
```bash
    pipx install .
```


## Usage

```bash
yt-tools --help
usage: yt-tools [-h] [--duration] [--transcript] [--transcript-ts {csv,json}] [--comments] [--metadata] [--lang LANG] url

yt (video meta) extracts metadata about a video, such as the transcript, the video's duration, and comments. Based on the yt tool from fabric (https://github.com/danielmiessler/fabric)

positional arguments:
  url                   YouTube video URL

options:
  -h, --help            show this help message and exit
  --duration            Output only the duration
  --transcript          Output only the transcript
  --transcript-ts {csv,json}
                        Output only the transcript with timestamps
  --comments            Output the comments on the video
  --metadata            Output the video metadata
  --lang LANG           Language for the transcript (default: English)
```