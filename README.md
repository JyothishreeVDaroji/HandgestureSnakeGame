\# Hand Gesture Controlled Snake Game



A classic Snake game reimagined with a modern twist! Control the snake's movement using hand gestures detected by your webcam.



\## Technologies Used



\* \*\*Python:\*\* The core programming language.

\* \*\*Pygame:\*\* A set of Python modules designed for writing video games.

\* \*\*OpenCV (`opencv-python`):\*\* Used for real-time video capture from the webcam and basic image processing.

\* \*\*MediaPipe (`mediapipe`):\*\* Google's open-source framework for building multimodal applied machine learning pipelines. Specifically, used for robust hand detection and landmark tracking.



\## Features



\* Classic Snake gameplay (eat food, grow, avoid collisions).

\* Intuitive hand gesture control: Move your hand left, right, up, or down to control the snake's direction.

\* Real-time hand landmark visualization on the webcam feed.

\* Score tracking.

\* Game over screen with restart option.



\## Setup and Installation



1\.  \*\*Prerequisites:\*\*

&nbsp;   \* Python 3.7+ (Python 3.10, 3.11, or 3.12 are recommended for MediaPipe compatibility).

&nbsp;   \* A working webcam.



2\.  \*\*Clone the repository:\*\*

&nbsp;   ```bash

&nbsp;   git clone \[https://github.com/YourUsername/HandGestureSnakeGame.git](https://github.com/YourUsername/HandGestureSnakeGame.git)

&nbsp;   cd HandGestureSnakeGame

&nbsp;   ```



3\.  \*\*Install dependencies:\*\*

&nbsp;   ```bash

&nbsp;   pip install opencv-python mediapipe pygame

&nbsp;   ```

&nbsp;   \*(Note: If you encounter issues with `mediapipe` installation, ensure your Python version is compatible. Python 3.13.x might not have pre-built wheels available yet for MediaPipe.)\*



\## How to Run the Game



1\.  Navigate to the project directory in your terminal:

&nbsp;   ```bash

&nbsp;   cd C:\\Users\\Jyothishree\\Desktop\\HandGestureSnakeGame

&nbsp;   ```

2\.  Run the main game script:

&nbsp;   ```bash

&nbsp;   python gesture\_snake.py

&nbsp;   ```

&nbsp;   (If you renamed your file from `gesture\_snake.py.txt` to `gesture\_snake.py`)



\## How to Play



\* Two windows will open: the "Hand Gesture Snake Game" (black screen) and "Webcam Feed (Hand Tracking)".

\* Position your hand clearly in front of your webcam in the "Webcam Feed" window.

\* Move your hand:

&nbsp;   \* \*\*Left:\*\* Snake moves left.

&nbsp;   \* \*\*Right:\*\* Snake moves right.

&nbsp;   \* \*\*Up:\*\* Snake moves up.

&nbsp;   \* \*\*Down:\*\* Snake moves down.

\* Eat the red food to grow and score points.

\* Avoid hitting the walls or the snake's own body.

\* \*\*To restart after "GAME OVER!":\*\* Click on the "Hand Gesture Snake Game" window to make it active, then press the 'R' key. Press 'Q' to quit.



\## Future Enhancements (Ideas)



\* Implement more complex gestures (e.g., finger counting for speed control, thumb up for pause).

\* Add sound effects for eating food and game over.

\* Introduce difficulty levels (adjust snake speed, food spawn rate).

\* Enhance the game over UI with more interactive options.

\* Explore using two hands for different controls.



---

\*Developed by \[Your Name or LinkedIn Profile Link]\*

