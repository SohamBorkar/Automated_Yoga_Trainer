# Yoga Posture Detection and Correction System

## Overview
The Yoga Posture Detection and Correction System is an AI-based application that analyzes yoga postures in real-time using deep learning. It provides instant feedback to users, helping them improve their poses and reduce the risk of incorrect postures. The system leverages TensorFlow’s MoveNet Thunder model for precise and quick pose estimation and correction.

## Features
- **Real-time posture analysis** using TensorFlow MoveNet
- **Instant feedback mechanism** for correcting incorrect yoga postures
- **Deep learning-based accuracy** with trained Convolutional Neural Networks (CNN)
- **User-friendly interface** for seamless interaction
- **Scalability** for various yoga asanas and movement analysis

## Technologies Used
- **Programming Language:** Python
- **Deep Learning Framework:** TensorFlow
- **Model Used:** MoveNet (Pose Estimation)
- **Libraries:** OpenCV, NumPy, Matplotlib
- **Deployment:** Flask (for Web API), Streamlit (for UI)

## How It Works
1. The system captures real-time video using a webcam.
2. It detects key body joints using MoveNet.
3. The model compares the detected posture with the ideal posture.
4. Users receive instant feedback and suggestions for correction.
5. Performance tracking and progress visualization for improvement.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yoga-posture-detection.git
   cd yoga-posture-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```

## Applications
- Personal fitness assistance
- Virtual yoga coaching
- Posture correction for physiotherapy
- AI-powered fitness tracking

## Research Contribution
This project was published as a research paper titled **“Aasana: Kinematic Yoga Posture Detection and Correction System using CNN”** in **ICDSAC 2023**, highlighting its accuracy and impact in yoga posture analysis.

## Future Improvements
- Integrating reinforcement learning for adaptive posture correction.
- Expanding the dataset to support a wider range of yoga postures.
- Developing a mobile application for accessibility.

## License
This project is open-source under the **MIT License**.

## Author
**Soham Borkar**  
Email: soham.borkar22@vit.edu  
LinkedIn: [Soham Borkar](https://www.linkedin.com/in/soham-borkar-4102342ba/)
