# Instance Segmentation Coursework

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

This repository contains the coursework for the **Instance Segmentation assignment** from the Course: Intelligent Transportation System Design of my 2nd MSc
The task was to create a sequence of frames simulating a **driving scene**, where the vehicle perceives and recognizes its environment using **instance segmentation algorithms**.



# Coursework Description
The project demonstrates how a vehicle can:
- Generate video-like sequential frames of a driving scene.
- Perform **instance segmentation** on each frame.
- Accurately detect and highlight objects surrounding the vehicle (e.g., cars, pedestrians, road elements).
- Visualize results in both **Jupyter Notebook** and with a separate Python script (`visualizer.py`).

This allows the vehicle to understand its environment in a structured way, enabling intelligent transportation applications.



# Repository Structure
- `Instance_Segmentation_Exercise_solved.ipynb` → Main Jupyter Notebook with the solution.  
- `visualizer.py` → Script to visualize instance segmentation outputs.  
- `.gitignore` → (local only, not tracked in repo).  



# Requirements
- **Python 3.8+**
- **Jupyter Notebook**
- Libraries:
  - `torch`, `torchvision`
  - `matplotlib`, `numpy`
  - `opencv-python`
  - (optional) Detectron2 or other segmentation frameworks if required.



# How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/NickosKokosal/Instance_Segmentation_Coursework.git
   cd Instance_Segmentation_Coursework
