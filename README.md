---

# Virtual Painting - Touchless Drawing Application

**Virtual Painting** is an interactive touchless drawing application that allows users to paint on a digital canvas using hand gestures. Developed using Python, OpenCV, and Mediapipe, the project uses real-time hand tracking to detect hand landmarks and allows users to draw in different colors by moving their hand in front of the webcam.

---

## Features

- **Hand Gesture Recognition**: Tracks hand movements using Mediapipe and OpenCV for touchless interaction.
- **Multiple Color Options**: Select from 4 colors (blue, green, red, yellow) for drawing.
- **Clear Canvas**: Option to clear the canvas with a gesture.
- **Real-Time Painting**: Draw directly on the canvas in real-time by moving your hand.

---

## Requirements

- Python 3.x
- OpenCV
- Mediapipe
- Numpy

---

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/virtual-painting.git
   cd virtual-painting
   ```

2. Install the required dependencies:

   ```bash
   pip install opencv-python mediapipe numpy
   ```

---

## Usage

1. Run the Python script:

   ```bash
   python virtual_painting.py
   ```

2. The application will open a webcam window. Use the following gestures:
   - **Thumb and forefinger close together**: Create a new drawing.
   - **Swipe near the "CLEAR" button**: Clear the canvas.
   - **Point your hand over any of the color boxes** to select the color.
   
3. **Press 'q'** to exit the application.

---

## How it Works

- **Hand Tracking**: The Mediapipe library is used to detect hand landmarks in real-time. The application identifies the position of the hand, and based on the gestures, it interprets the drawing actions.
- **Color and Drawing**: Once the color is selected, hand movements are tracked to create strokes on the canvas, allowing users to draw and interact with the virtual painting environment.

---

## Contributing

Feel free to fork this project and make contributions. If you have suggestions or improvements, open an issue or submit a pull request.

---

## License

This project is open-source and available under the MIT License.

---
