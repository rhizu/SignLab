# SignLab – Real-Time Sign Language Recognition & Learning System

## Overview

SignLab is an interactive real-time American Sign Language (ASL) recognition and learning platform designed to improve communication between Deaf and non-signing communities.

Unlike traditional recognition systems that only translate gestures, SignLab focuses on interactive learning and practice, allowing users to learn, perform, and receive real-time feedback using a webcam-based system.

The application uses MediaPipe hand landmark detection and machine learning models to recognize ASL gestures in real time.

## Key Features:

### Real-Time Gesture Recognition:

- Detects ASL gestures using webcam input

- Uses MediaPipe hand landmark tracking for precise detection

- Displays predicted gestures instantly on screen

### Interactive Learning System:

- Practice ASL letters in real time

- Immediate feedback on gesture accuracy

- Helps users improve through repetition and visualization

### Progress Tracking:

- Tracks user learning progress

- Enables self-evaluation and improvement over time

### Tech Stack:

- Frontend: Web-based UI (React / HTML / CSS)

- Machine Learning: CNN / Classification Model

- Computer Vision: MediaPipe Hand Landmarks

- Backend: Python

- Core Concept: Real-time gesture recognition system

### System Architecture:

- Webcam captures real-time hand gestures

- MediaPipe extracts hand landmark features

- ML model classifies gestures into ASL letters

- Output is displayed instantly on the interface

- System provides feedback for learning and validation
