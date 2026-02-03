# Model Files

Due to GitHub's file size limitations, the following large files are not included in the repository:

## Required Model Files:
- `best.pt` - Trained YOLOv8 model for weapon detection (~22MB)
- `yolov8m.pt` - Base YOLOv8 medium model (~52MB)  
- `alarm.mp3` - Alarm sound file

## How to Get Model Files:

### Option 1: Download Pre-trained Models
Download the original trained model from the source repository or train your own using `train.py`.

### Option 2: Use YOLOv8 Base Model
The base `yolov8m.pt` model will be automatically downloaded by ultralytics when you first run the detection scripts.

### Option 3: Train Your Own Model

```bash
# Prepare your dataset in the required format
# Then run:
python train.py
```

This will create a `best.pt` file with your trained model.

## Alarm Sound
Add your own `alarm.mp3` file to the project root directory for alarm functionality.

## Quick Start Without Pre-trained Model
The scripts can work with the base YOLOv8 model, but for weapon-specific detection, you'll need the trained `best.pt` model.
