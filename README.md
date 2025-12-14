# 李's Detection

Li's Detection is a edge detection algorithm built from ground up able identify edges in an image, has capability that penetrating obfuscated process such as edge disorintation, layer-adding, cropping and rotation.

### Performance
- Detection Performance:
  - Ability to adopt and changing parameters for large region detection to bypass obfucation
  - Natural Image:
    - Robust performance on-pair gradient detecting algorithms like Canny
    - Demos:
      - Human with background:
        - ![alt text](./README_Images/Figure_1.png)
      - Sheep:
        - ![alt text](./README_Images/sheep.png)
  - Obsucated Image:
    - Far superior than gradiant based algorithms 
    - Demos:
      - Hcaptcha:
        - ![alt text](/README_Images/2.png)

- Execution Performance:
  - Optimized with Numpy, on Python:
    - An average 400x400 image per channel executing speed is 0.02s
    - About 2 - 6 times slower than optimized in C while in pure Python

### Demos:

- Natural Image:
  - Robust performance on-pair gradient detecting algorithms like Canny
  - Demos:
    - Natural Image - Human
    - Natural Image - Multi-lines
    - Natural Image - ProtonMail CAPTCHA
  
- Obsucated Image:
  - Far superior than gradiant based algorithms 
  - Demos:


Using Li's Detection processing images, finding objects with brutal-force, action with Selenium Actionchain, parallel with multiprocessing

[![Video Thumbnail](https://img.youtube.com/vi/VdhTPZG-UhI/0.jpg)](https://www.youtube.com/watch?v=VdhTPZG-UhI)
