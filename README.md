# 李's Detection

Li's Detection is a robust pixel analyzing, edge detecting algorithm supports color/gray multi-channel edge detection, pixel-level accuracy edge detection on "natural images", and domonstrated de-obfucating capability on obfuscated images like CAPTCHAs.

### Performance
- Detection Performance:
  - Natural Image:
    - Robust performance on-pair gradient detecting algorithms like Canny
  - Obsucated Image:
    - Far superior than gradiant based algorithms
- Execution Performance:
  - Optimized with Numpy, on Python:
    - An average 400x400 image per channel executing speed is 0.02s
    - About 2 - 6 times slower than optimized in C while in pure Python
  

### Demos
  - Natural Images:
    - Human with background (color -> whiten):
      - ![alt text](/README_Images/detector_jennie.png)
    - Sheep (color -> color):
      - ![alt text](/README_Images/detector_sheep.png)
  - Obsucated Images:
      - Hcaptcha:
        - ![alt text](/README_Images/detector_hcaptcha1.png)


Related:

[![Video Thumbnail](https://img.youtube.com/vi/VdhTPZG-UhI/0.jpg)](https://www.youtube.com/watch?v=VdhTPZG-UhI)
