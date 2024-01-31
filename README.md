
# ROV-UnderWater-Image-Enhancer

The ROV Underwater Image Enhancer project provides the following features:

1. **Image Color Corrector**: Corrects the color of underwater images.
2. **Direction Detector**: Detects the direction of objects in underwater images.
3. **Thickness Measurement**: Measures the thickness of objects in underwater images.
4. **Helping Modules**: Includes modules like Channel Analyzer and Histogram Analyzer for testing and analysis purposes.

The project is built using Object-Oriented Design to make it more organized and structured.

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/python-arch/ROV-Underwater-Image-Enhancer.git
   ```

2. Install dependencies:

   ```sh
   pip install -r requirements.txt
   ```

## Usage

### Test Images

You can find all the test images under the folder **images**.

### Running Scripts

All the scripts work in a similar manner:

1. Navigate to the `modules` folder.
2. Choose the module you want to run or navigate to `/helping_modules`.
3. Open the terminal and run the script:

   ```sh
   python script.py
   ```

4. When prompted, enter the number of the image to process (images are numbered from 1 to 16).
5. **Enter the image number only**.
6. Depending on the script:

   - If running the `color_corrector`, the output will be saved to `/color_corrected_images`.
   - If running the `direction_detector`, the output will appear on the screen (samples are available in the `direction_detection_samples` folder).
   - If running the `measure_thickness`, the output will appear in the terminal.
   - If running any of the helping modules, the output will be displayed as a plot figure.
