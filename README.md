# VIS-À-VIS Live

Exhibition prototype of the VIS-À-VIS Dialogue Layer: a 180° clip-camera view that tracks hands and non-manual signals (face) and interprets signs in real time on an iPad.

- Sign model and feature pipeline: ported from [GestureSign](https://github.com/shashank11yadav/GestureSign) by Shashank Yadav (MIT, see `LICENSE-GestureSign.txt`)
- Training data: Kaggle "Google – Isolated Sign Language Recognition" (asl-signs, CC BY 4.0)
- Landmarks: Google MediaPipe Holistic (Apache-2.0)

Static site: open `index.html` over https (Netlify). No build step.
