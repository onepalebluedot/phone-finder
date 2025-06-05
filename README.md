# Phone Finder App

A real-time phone detection web application that uses TensorFlow.js and your device's camera to detect cell phones in the frame. When a phone is detected with high confidence, the app freezes the frame and highlights the detected phone.

## Features

- Real-time object detection using TensorFlow.js
- Works directly in the browser with no server required

## How It Works

The app uses the COCO-SSD model to detect objects in real-time through your device's camera feed. When a cell phone is detected with high confidence, the app will:
1. Freeze the current frame
2. Draw a bounding box around the detected phone
3. Display a "PHONE DETECTED" message

## Getting Started

### Prerequisites

- A working webcam
- Internet connection (required for loading the TensorFlow.js model)

### Installation

No installation is required! Simply open the `phone_finder.html` file in your web browser.

### Usage

1. Open `phone_finder.html` in your web browser
2. Click "Start Camera" when prompted to allow camera access
3. Point your camera at a phone or other objects
4. The app will automatically detect phones and highlight them
5. Click "Stop Camera" when done to release the camera

## Technical Details

- Built with vanilla JavaScript (no frameworks)
- Uses TensorFlow.js for machine learning in the browser
- Implements the COCO-SSD pre-trained model for object detection
- Real-time processing with requestAnimationFrame for smooth performance

## Browser Compatibility

This app works best in modern browsers with WebGL support. 

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- [TensorFlow.js](https://www.tensorflow.org/js/) for making machine learning accessible in the browser
- [COCO-SSD](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd) model for object detection
- [Google's Web.Dev](https://web.dev/) for web development best practices

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Author

Onepalebluedot

---

*Note: This app processes all video data locally in your browser. No images or video are sent to any server.*
