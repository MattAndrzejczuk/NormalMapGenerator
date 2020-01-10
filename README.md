# Normal Map Batch Generator

Normal Map Generator is a tool written in Python

## Required

- Python
- Scipy
- Numpy

## Usage

#### Batch entire directory with height maps:
  `for file in *.jpg; do python3 normal_map_generator.py "$file"; done`

#### Single file:
./normal_map_generator.py input_file --smooth SMOOTH_VALUE -- intensity INTENSITY_VALUE

### Required arguments:

#### input_file            
input image path

### Optional arguments:

#### -h, --help            
Show help message

#### -s SMOOTH_VALUE, --smooth SMOOTH_VALUE
Smooth gaussian blur applied on the image

#### -it INTENSITY_VALUE, --intensity INTENSITY_VALUE
Intensity of the normal map
