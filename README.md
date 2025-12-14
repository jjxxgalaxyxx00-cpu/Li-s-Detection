# 李's Detection

Li's Detection is a robust pixel analyzing, edge detecting algorithm supports color/gray multi-channel edge detection, domonstrated de-obfucating capability on obfuscated images like CAPTCHAs using Blur, edge disorientation to detect "true edges", and pixel-level accuracy robust detecting performance on "natural images" on-pair traditional edge detecting algorihtms.

Language: Written in Python with Numpy
Optimized speed with Numpy, about 2 - 6 times slower than C.

### Performance
- Detection Performance:
  - Natural Images:
    - Robust performance on-pair gradient detecting algorithms like Canny
    - Demos:
      - Human with background (color -> whiten):
        - ![alt text](/README_Images/detector_jennie.png)
      - Sheep (color -> color):
        - ![alt text](/README_Images/detector_sheep.png)
  - Obsucated Image:
    - Far superior than gradiant based algorithms
     - Hcaptcha:
        - ![alt text](/README_Images/detector_hcaptcha1.png)
- Execution Performance:
  - Optimized with Numpy, on Python:
    - An average 400x400 image per channel executing speed is 0.02s
    - About 2 - 6 times slower than optimized in C while in pure Python
  
Related:

[![Video Thumbnail](https://img.youtube.com/vi/VdhTPZG-UhI/0.jpg)](https://www.youtube.com/watch?v=VdhTPZG-UhI)
