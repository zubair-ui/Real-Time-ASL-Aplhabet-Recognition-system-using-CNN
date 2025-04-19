# Real-time Webcam Feed and Hand Gesture Recognition

This project uses a real-time webcam feed to recognize hand gestures based on a trained model. The webcam feed is processed and predictions are made based on the detected hand region.

## Dataset Information

This project relies on a dataset for hand gesture classification, and the dataset needs to be downloaded and organized in the project directory.
**Dataset Link**: [Hand Gesture Dataset](https://www.kaggle.com/ahmedtaki/hand-gesture-recognition-dataset)

Please note that you need to download the dataset manually from the above link and place it in the following directory structure:

```
project_root/
    └── dataset/
        └── [Your dataset files here]
```

## Prerequisites

Before running this project, make sure you have the following dependencies installed:

### Python Dependencies

You can install the required Python packages.

### Required Python Libraries

- `tensorflow`
- `opencv-python`
- `Pillow`
- `numpy`
- `tkinter`

## License

This project is licensed under the MIT License.

---

### Notes

- Make sure your webcam is connected and accessible.
- Ensure that you have the appropriate permissions to use the camera and the dataset.
