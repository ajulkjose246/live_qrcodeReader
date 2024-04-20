# live_qrcodeReader

live_qrcodeReader is a Python-based project designed to read and decode QR codes in real-time using a webcam. It utilizes the OpenCV library for image processing and the Pyzbar library for decoding QR codes. This application captures video frames from the webcam, identifies QR codes within the frames, and decodes their content, displaying the result on the screen. It's particularly useful for quick data retrieval from QR codes in various applications such as inventory management, event ticketing, and contactless information sharing.

## Features

- **Video Capture**: Uses the webcam to capture live video frames.
- **QR Code Detection**: Identifies QR codes within the video frames.
- **Decoding**: Extracts and decodes the data contained in the QR codes.
- **Display**: Shows the decoded information on the user's screen.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/live_qrcodeReader.git
    ```

2. Navigate to the project directory:

    ```bash
    cd live_qrcodeReader
    ```

3. Install the required packages:

    ```bash
    pip install opencv-python
    pip install numpy
    pip install pyzbar
    ```

## Usage

Run the `main.py` file to start the application:

```bash
python main.py
