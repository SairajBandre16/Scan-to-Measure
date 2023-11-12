
# Scan to Measure

Scan to Measure is a Python-based project that utilizes OpenCV and ArUco markers to detect the height and width of objects through a webcam. This project is useful for measuring physical dimensions using computer vision techniques.

## Prerequisites

Before running the application, make sure you have the following installed:

- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)

## Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/SairajBandre16/scan-to-measure.git
   cd scan-to-measure
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   python scan_to_measure.py
   ```

   This will launch the webcam and start measuring objects using ArUco markers.

## Usage

- Position the object within the view of the webcam.
- Ensure that an ArUco marker is visible in the frame.
- The application will detect the object and display its height and width.



## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

