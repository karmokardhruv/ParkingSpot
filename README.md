# Parking Space Detection System

This repository contains a parking space detection system that uses computer vision to determine parking spot occupancy from video or image data. It can be used to analyze footage from parking lots to track available parking spaces in real-time.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Structure](#structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation
To install the required dependencies, ensure Python 3.7 or higher is installed, then run the following command:

```bash
pip install -r requirements.txt
```

## Usage
To use the system for parking space detection:
1. Add your video or image data to the repository.
2. Modify the configurations (if needed) in the code files to point to the correct data paths.
3. Run the `Detect_Spots.ipynb` Jupyter Notebook to start the detection system.

## Structure
- `clf-data`: Contains training data for model training.
- `Detect_Spots.ipynb`: The Jupyter Notebook script that processes video data for parking space detection.
- `Train_SVC.ipynb`: Jupyter Notebook for training the support vector machine classifier.
- `mask_1920_1080.png`: Image mask for parking spot detection.
- `parking_1920_1080_loop.mp4`: Video sample for detection.
- `model.p`: The trained SVM model used to classify parking spots.
- `processed_parking_lot_video.avi`: Output video showing detected parking spots.
- `requirements.txt`: Contains required Python libraries for installation.

## Contributing
We welcome contributions. If you would like to contribute, please follow these steps:
1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Submit a pull request explaining your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
If you have questions or suggestions, please open an issue or contact me at [dhruv123karmokar@gmail.com].

