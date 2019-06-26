# JetRacer

JetRacer is an educational AI racecar using NVIDIA Jetson Nano that is

* Affordable - ~$250 including Jetson Nano

* Educational - Examples from basic motion to AI road following
* Fun! - Interactively programmed from your web browser

To get started, pick a [car](#cars) and follow the instructions.

## Cars

| Model | Description | Picture | Instructions |
|------|----------|-------------|--------------|
| NVIDIA | 1/18th scale with manual override | <img src="https://lh3.googleusercontent.com/NKCZUpv25TTaZ4PFVbxIUZkzVP7l90xhGrmiXJo4R6edUQnWp5coYkM7J1T9pZOnHM6KyhmdxXwpsn7or_8r--yNva_fPAdjZnqdNU3_NUSK7iGxqFzQ0Ucjb0F4WucMUg4MRYOJ5so" max-height=128> | [docs/nvidia/instructions.md](docs/nvidia/instructions.md) |

## Usage

### Create racecar

```python
from jetracer.nvidia_racecar import NvidiaRacecar

car = NvidiaRacecar()
```

### Control

```python
car.steering = 0.3
car.throttle = 0.6
```

## Examples

### Example 1 - Basic motion

### Example 2 - Road following

## See also

* [JetBot](http://github.com/NVIDIA-AI-IOT/jetbot) - An educational AI robot based on NVIDIA Jetson Nano

* [JetCam](http://github.com/NVIDIA-AI-IOT/jetcam) - An easy to use Python camera interface for NVIDIA Jetson
* [JetCard](http://github.com/NVIDIA-AI-IOT/jetcard) - An SD card image for web programming AI projects with NVIDIA Jetson Nano
* [torch2trt](http://github.com/NVIDIA-AI-IOT/torch2trt) - An easy to use PyTorch to TensorRT converter
