## Features

- Take screenshot of entire display instantly.
- Capture your screen easily with ffmpeg.
- Interactively select a region or a window on the screen and capture the selected region.
- Audio recording - Capture your mic when recording the screen.
- Define delay time before taking screenshot or recording.
- Define timer for how long you want to record your screen.
- Define framerate, video codec and other parameters directly.

## Limitation
- Does not work for multi-monitor capturing.

## Requirements

- ffmpeg
- slop

## Usage

- To record the screen with audio(microphone)
`ffcapture -a -v -o screenrecord.mkv`
- To take a screenshot after 5 seconds
`ffcapture -d 5 -o screenshot.png`
- For more information, run `ffcapture --help`

## License
Copyright (c) 2021 soura99

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
