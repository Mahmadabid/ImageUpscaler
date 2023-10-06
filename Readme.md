# Image Processing Tool

This repository contains an image processing toolkit that provides functionalities such as upscaling an image, converting pixel data to an image, and extracting pixel data from an image. Additionally, it provides a GUI-based application to interactively execute these operations.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Usage](#usage)
- [Files Description](#files-description)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

## Prerequisites

- Python (tested with version 3.x)
- [Pillow (PIL)](https://pillow.readthedocs.io/en/stable/)
- [PyQt5](https://pypi.org/project/PyQt5/)
- [PyQt5-tools](https://pypi.org/project/pyqt5-tools/)

## Setup

1. Clone this repository:

```ruby
git clone [https://github.com/Mahmadabid/ImageUpscaler]
```

2. Navigate to the project directory:

```ruby
cd ImageUpscaler
```

3. Install the required dependencies:

```ruby
pip install Pillow PyQt5 pyqt5-tools
```


## Usage

To utilize the GUI application:

```ruby
python Gui.py
```

Follow the on-screen instructions to select and execute the desired image processing operation.

## Files Description

- `ImgUpscaler.py`: Upscales a sqaure image to 4x its original size.
- `Pixel_to_Img.py`: Converts pixel data from a text file back to an image.
- `Img_to_Pixel.py`: Extracts pixel RGB values from an image and saves them to a text file.
- `uniquePath.py`: Utility script that generates unique filenames.
- `Gui.py`: GUI application integrating all the above functionalities.
