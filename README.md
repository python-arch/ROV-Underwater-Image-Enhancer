# ROV-UnderWater-Image-Enhancer

The project Basically provides the following:
  1. Image Color Corrector
  2. Direction detector
  3. Thickness Measurement
  4. Helping modules (Channel Analyzer , Histogram Analyzer) for testing and anaylsis purposes.

The project is built using Object-Oriented-Design to make it more organized and structured.

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
You can find all the test images under the folder **images**. All the scripts work in similar manner:
1. Navigate to the modules folder
2. Choose the needed module to run or /helping_modules
3. Open the terminal and write:
   ```sh
   python script.py
   ```
4. A message will pop-up asking you to enter the number of the image to process , the images are numbered as shown from 1 to 16
5. **Enter the image number only**
6. Depending on the script:
   6.6. If the color_corrector was to run , the output will be saved to /color_corrected_images
   6.7. If the direction_detector , the output will appear on the screen (I have saved already tested images in the direction_detection_samples) folder
   6.8. If the measure_thickness , the output will appear on the terminal
   6.9. If any of the helping modules , the output will appear as a plot figure

