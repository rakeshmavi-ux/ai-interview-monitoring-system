# AI Interview Monitoring System

An AI-driven system designed to assist in monitoring online interviews by analyzing candidate behavior and identifying potential irregularities during an interview session.

## Overview

Online interviews can be difficult to monitor consistently, especially when interviews are conducted remotely.

This project explores the use of computer vision and artificial intelligence techniques to analyze visual information during an interview and provide monitoring-related observations.

The system is designed as an assistance tool rather than a replacement for human interviewers.

## Features

- Face detection and monitoring
- Candidate presence detection
- Head and facial movement analysis
- Basic monitoring of unusual behavior
- Real-time video processing
- AI/computer-vision based analysis
- Interview monitoring interface

## Technologies Used

- Python
- OpenCV
- Computer Vision
- Artificial Intelligence / Machine Learning
- NumPy
- Machine Learning libraries

## Project Architecture

```text
Candidate
    │
    ▼
Web Camera / Video Input
    │
    ▼
Video Processing
    │
    ├── Face Detection
    │
    ├── Head / Facial Movement Analysis
    │
    └── Behavior Monitoring
    │
    ▼
Monitoring Results
    │
    ▼
Interview Monitoring Interface
```

## How It Works

1. The system receives video input from the candidate's camera.
2. Video frames are processed using computer-vision techniques.
3. The candidate's face and relevant visual features are detected.
4. The system analyzes selected movements and monitoring conditions.
5. The detected information is used to generate monitoring observations.
6. The results can be reviewed as part of the interview process.

## Installation

Clone the repository:

```bash
git clone https://github.com/rakeshmavi-ux/ai-interview-monitoring-system.git
cd ai-interview-monitoring-system
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the environment.

### Windows

```bash
venv\Scripts\activate
```

### macOS / Linux

```bash
source venv/bin/activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the application using:

```bash
python src/main.py
```

The exact command may vary depending on the final project implementation.

## Project Status

**Status:** Completed / Academic Project

This project was developed as part of my Bachelor of Engineering in Computer Science and Engineering.

## Future Improvements

- Improve real-time detection accuracy
- Add additional behavioral indicators
- Improve the user interface
- Add interview session reports
- Improve model performance
- Add secure data handling
- Deploy the system as a web application

## Privacy

This project is intended for academic and technical exploration of AI-assisted interview monitoring.

Any real-world implementation should consider user consent, privacy, data protection, and the limitations of automated behavioral analysis.

## Author

**Rakesh Mavillapalli**

Computer Science and Engineering Graduate

GitHub:  
https://github.com/rakeshmavi-ux

## License

This project is licensed under the MIT License.
