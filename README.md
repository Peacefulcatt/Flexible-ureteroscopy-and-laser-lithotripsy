# Flexible Ureteroscopy and Laser Lithotripsy Object Detection

This repository contains a Python script tailored for detecting and measuring objects in Flexible Ureteroscopy and Laser Lithotripsy (FURSL) footages. The script leverages the OpenCV library to perform advanced image processing tasks, including color filtering, contour detection, and bounding box calculations.

## Features

- Detects and tracks relevant objects in FURSL video footages.
- Draws bounding boxes around the detected objects for easy visualization.
- Calculates object dimensions, including height along the left and right "touching arms."
- Provides interactive adjustments with keyboard shortcuts.
- Offers a customizable grid overlay on the video frame.

## Requirements

- Python 3.x
- OpenCV (cv2) library

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/flexible-ureteroscopy-detection.git
   cd flexible-ureteroscopy-detection
   ```

2. Install the required dependencies (if not already installed):

   ```bash
   pip install opencv-python
   ```

3. Customize the `grid_space` and `diameter` variables in the script to match your specific FURSL setup.

4. Update `video_path` with the path to your Flexible Ureteroscopy and Laser Lithotripsy video footage.

5. Run the script:

   ```bash
   python flexible_ureteroscopy_detection.py
   ```

6. During video playback:
   - Press 'p' to pause/play the video.
   - Press '1' to increase grid density.
   - Press '2' to decrease grid density.
   - Press '4' to increase object diameter measurement.
   - Press '5' to decrease object diameter measurement.
   - Press 'esc' to exit the program.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

The script's design is inspired by various image processing techniques and harnesses the capabilities of the OpenCV library. It has been optimized for Flexible Ureteroscopy and Laser Lithotripsy applications.

---

Remember to replace `"your-username"` with your GitHub username in the clone URL and provide any additional information specific to your project's goals and requirements. This README will help convey the purpose and functionality of your repository effectively.
