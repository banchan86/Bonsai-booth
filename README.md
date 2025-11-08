# Bonsai Booth

Live demos for the Society for Neuroscience (SfN) conference.

## Examples

- **2afc** - Two-alternative forced choice behavioural task
- **CorridorVR** - Virtual reality corridor navigation
- **MoveNet** - Real-time pose estimation using MoveNet
- **MoveNetGame** - Interactive game controlled by pose detection
- **NeuralDecoder** - Neural signal decoding pipeline
- **PanTilt** - Camera pan-tilt control with screen VR
- **Rfid** - RFID reader integration
- **SpinnakerDemo** - FLIR camera acquisition demo
- **Theremin** - Audio synthesis controlled by movement

## Getting Started

### Installation

1. Download the [latest Bonsai installer (v2.9.0)](https://bonsai-rx.org/docs/articles/installation.html)
2. Run `Bonsai.exe` and click through to install.

### Running Examples

1. Navigate to any example folder (e.g., `examples/MoveNet/`)
2. Double-click on the workflow to launch the workflow and bootstrap the local Bonsai environment

## Repository Structure

```
examples/     Demonstration workflows
data/         Location to store data for running workflows
packages/     Pre-downloaded NuGet packages for bootstrapping offline
lib/          Store of shared dll files
models/       Place for storing model data
```