# Minecraft Ore Detection using YOLOv4-tiny

This project implements a real-time ore detection system in Minecraft using the YOLOv4-tiny neural network. The system analyzes the game screen to highlight ores, making resource gathering easier for players.

## Features

- Real-time detection of Minecraft ores.
- Utilizes YOLOv4-tiny for fast and efficient object detection.
- Customizable for different Minecraft versions and resource packs.

## Prerequisites

- Python 3.6 or higher
- OpenCV
- TensorFlow
- PyTorch
- Other dependencies in `requirements.txt`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/M117n/minecraft_ore_dectect.git
   ```

2. Navigate to the project directory:
```bash
cd minecraft_ore_dectect
```
3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

##Usage
1. Start Minecraft in windowed mode.
2. Run the detection script:
```bash
python detect.py
```
3. The script will display a real-time feed with highlighted detected ores.

## Configuration
- Edit config.yaml to adjust parameters like confidence thresholds, model paths, or screen capture settings.
- 
## Contributing
Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
1. YOLOv4-tiny for the base detection model.
2. OpenCV and TensorFlow communities for their tools and documentation.

##Contact
For any questions or suggestions, please open an issue or contact the repository owner directly.
