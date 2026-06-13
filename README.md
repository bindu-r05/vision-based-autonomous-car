# Vision-Based Gesture and Pedestrian Interactive Autonomous Car

## Overview

This project demonstrates a vision-based autonomous vehicle capable of interacting with humans using computer vision techniques. The system was developed on the AutoAuto platform and uses real-time image processing to recognize gestures and respond to pedestrian movement.

The vehicle can detect human gestures, follow pedestrians, and perform interactive actions such as stopping, turning, and reversing.

---

## Objectives

- Develop a human-aware autonomous vehicle
- Implement gesture-based vehicle control
- Detect and interact with pedestrians
- Demonstrate real-time decision making using computer vision

---

## Technologies Used

- Python
- OpenCV
- NumPy
- AutoAuto Platform
- Computer Vision

---

## System Features

### Gesture Recognition

The system detects large motion patterns using:

- Frame differencing
- Grayscale conversion
- Thresholding
- Contour analysis

A detected palm gesture can trigger vehicle actions such as:

- Stop
- Turn Right
- Change Direction

---

### Pedestrian Interaction

The vehicle continuously monitors its surroundings and:

- Detects pedestrians
- Follows moving pedestrians
- Reverses when pedestrian behavior changes

This creates a simple human-vehicle interaction system.

---

## Methodology

1. Capture camera frames
2. Process frames using OpenCV
3. Detect motion using frame differencing
4. Extract contours
5. Identify gestures and pedestrians
6. Execute vehicle commands

---

## Key Learning Outcomes

- Computer Vision Fundamentals
- Autonomous Vehicle Control
- Human-Vehicle Interaction
- Real-Time Image Processing
- Embedded Autonomous Systems

---

## Team Members

- Bindu R
- Aashirvad A Poojary
- Khushi K
- Vedant Mahalle

---

## Documentation

The complete project report is included in this repository.

---

## Future Scope

- Deep learning based gesture recognition
- Obstacle avoidance
- Multi-gesture control
- Autonomous navigation
- Advanced pedestrian tracking
