
# Semi-automated Batoid Detection, Tracking and Classification ipeline

## Overview

This repository contains the deep-learning pipeline developed to automate the detection, identification, and tracking of batoids from Baited Remote Underwater Video Systems (BRUVS) in the Gulf of California. The system leverages YOLOv11 for baseline detection and BoT-SORT for tracking. A multiclass DenseNet-121 classifier for scalable taxonomic resolution and calculating MaxN abundance metrics.


## Getting Started
1. Installation

Bash
git clone https://github.com/maclopo/batoid-detector.git
cd batoid-detector
pip install -r requirements.txt

