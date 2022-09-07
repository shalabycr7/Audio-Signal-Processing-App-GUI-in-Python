![](https://github.com/shalabycr7/Audio-Signal-Proccessing-App-GUI-in-Python/blob/Features/Cover%20Design.png)

# Audio Signal Processing App

> This Is A Simple GUI Application To Manipulate Audio Files By Modifying The Audio Wave Form And Display It Using
> Python

### Requirements

* ##### Install FFmpeg

* You Need To Install `FFmpeg` From This
  Guide [Install FFmpeg on Windows](<https://www.wikihow.com/Install-FFmpeg-on-Windows>)

* ##### Required Packages

> Make Sure You Install The Python Packages Globally (System-Wide) using `pip install <Pakage Name>`

| Python Package | Version  |
|----------------|----------|
| `matplotlib`   | `3.5.3`  |
| `numpy`        | `1.23.2` |
| `pyttsx3`      | `2.90`   |
| `ttkbootstrap` | `1.9.0`  |
| `winsound`     | `3.5.3`  |
| `pydub`        | `0.25.1` |
| `scipy`        | `1.9.1`  |

### Core Features

* Show Audio File Information Such As:
    * File Type (Supports Only `.Wav` Files For Now )
    * Number Of Channels
    * Audio Frame Rate
    * Maximum Audio Amplitude
    * Audio File Duration
* Modify The Audio File By:
    * Increasing/Decreasing The Amplitude
    * Increasing/Decreasing Audio Speed
    * Increasing/Decreasing Audio Delay (Shift)
    * Reversing The Audio
    * Add An Echo Effect
* Represent The Audio Wave Form For Both Original And Modified Files
* The Ability To Play Both Audio Files
* Text To Speach Functionality
* Export Both The New Modified Audio File And The Transcript TTS File In A New Directory `Audio output`
* Convolution Operations For Some Elementary Signals
* LTI System Functionality:
    * Convert Between Zeros And Poles Formula To H (s) Represented In Numerator/Denominator Formula
* Support For Stereo Audio Files
* Support Dark Mode Theme

### Screenshots

#### Main Interface

![Main Interface][s1]
![Main Interface In Dark Mode][s2]

#### Convolution Interface

![Main Interface For Convolution][s3]
![Main Interface For Convolution][s4]

#### TTS Interface

![TTS Interface][s5]


[s1]: https://github.com/shalabycr7/Audio-Signal-Proccessing-App-GUI-in-Python/blob/b9debebd0c047fa9d33f3abca1ebfea73e21faf2/Screenshots/11.png "Main Interface"

[s2]: https://github.com/shalabycr7/Audio-Signal-Proccessing-App-GUI-in-Python/blob/b9debebd0c047fa9d33f3abca1ebfea73e21faf2/Screenshots/22.png "Main Interface In Dark Mode"

[s3]: https://github.com/shalabycr7/Audio-Signal-Proccessing-App-GUI-in-Python/blob/b9debebd0c047fa9d33f3abca1ebfea73e21faf2/Screenshots/33.png "Main Interface For Convolution"

[s4]: https://github.com/shalabycr7/Audio-Signal-Proccessing-App-GUI-in-Python/blob/b9debebd0c047fa9d33f3abca1ebfea73e21faf2/Screenshots/44.png "Main Interface For Convolution"

[s5]: https://github.com/shalabycr7/Audio-Signal-Proccessing-App-GUI-in-Python/blob/b9debebd0c047fa9d33f3abca1ebfea73e21faf2/Screenshots/55.png "TTS Interface"

### Task List

- [ ] Add Support For More Audio Formats like `.mp3`
- [x] Add Support For Stereo Files
- [x] Remove Deprecated Audio Libraries/Functions

### Changelogs

* **V 0.5**
    * Added Validation For User Input :heavy_check_mark:
    * Added Splash Screen :heavy_check_mark:

* **V 0.4**
    * Fixed Dark Mode Interface Issues :heavy_check_mark:
    * Fixed Some Echo Issues When Importing Stereo Files :heavy_check_mark:
    * Code Reformat :heavy_check_mark:

* **V 0.3**
  > Playing Audio Does Not Freeze The App Anymore
    * Some minor improvements to the code :heavy_check_mark:
    * Fixed Minor Bugs And Improved Optimizations :heavy_check_mark:
    * Added Support For Playing Audio Async :heavy_check_mark:
    * Added Stop Button :heavy_check_mark:
    * Display Audio File Duration :heavy_check_mark:

* **V 0.2**
    * Added Support For Stereo Audio Files :heavy_check_mark:
    * Fixed Minor Bugs And Improved Optimizations :heavy_check_mark:
    * Added Convolution For Some Elementary Signals :heavy_check_mark:
    * Support For Dark Mode :heavy_check_mark:
* **V 0.1**
    * Initial Release :warning:

### Supported Versions

The app was tested on the following version of python

| Version | Supported          |
|---------|--------------------|
| 3.10    | :white_check_mark: |

