# Hand Gesture Recognition Using 3D LiDAR Sensor

## Project Overview
This project explores and evaluates various technologies for enhancing user interaction through gesture recognition. Using 3D LiDAR sensors and advanced neural network models, the system predicts both static and dynamic hand gestures in real-time, aiming to provide robust and accurate gesture recognition solutions.

## Objectives
- Develop a gesture recognition system leveraging multiple approaches and tools.
- Evaluate the effectiveness and accuracy of each method.
- Identify the best techniques for reliable and efficient gesture recognition.

## Approaches and Tools
1. **Gesture Kit & AI Model with User Selection**:
   - Combines GestureKit for dynamic gestures and HandPosture AI for static gestures.
   - Uses user-selection buttons to switch between static and dynamic gesture detection modes.

2. **3D Convolutional Neural Network (CNN) AI Model**:
   - Employs 3D CNNs for real-time spatial and temporal gesture prediction.
   - Provides robust noise cancellation and gesture prediction for dynamic and static gestures.

3. **STMicroelectronics Merged Solution**:
   - Integrates both static and dynamic gesture models for seamless gesture recognition without user intervention.
   - Uses STMicroelectronics’ STSW-IMG035_EVK and STM32CubeAI for real-time implementation.

4. **Prompt-Based Gesture Recognition (using GPT API)**:
   - Implements real-time gesture prediction by analyzing trends in sensor data.
   - Combines statistical analysis with GPT for improved prediction accuracy.

## Gesture Categories
### Dynamic Gestures
- Palm Up, Palm Down, Palm Left, Palm Right, Palm Forward, Palm Backward
- Double Tap, Left, Right, Forward, Backward

### Static Gestures
- Flat Hand, Thumbs Up, Thumbs Down, Heart, Cross Hands, Fist

## Key Components
1. **Sensor Data Collection**:
   - Real-time data collection using LiDAR sensors and parsing raw data into frames.
2. **Preprocessing**:
   - Extracts meaningful features like mean, standard deviation, and center of gravity.
3. **Gesture Prediction**:
   - Combines statistical trends with AI models for accurate gesture recognition.
4. **Visualization**:
   - Tkinter-based GUI for real-time gesture display.

## Test Accuracy
- **Gesture Kit & AI Model**: Achieved reliable recognition for individual dynamic and static gestures.
- **3D CNN AI Model**: Provided enhanced prediction accuracy with robust real-time performance.
- **STMicroelectronics Merged Solution**: Seamlessly predicted both gesture types without user intervention.
- **Prompt-Based Gesture Recognition**: Efficiently combined trends with AI for high-accuracy predictions.

## Tools and Frameworks
- **GestureKit**: For dynamic gesture recognition.
- **STMicroelectronics STSW-IMG035_EVK**: Merged solution for static and dynamic gestures.
- **Neural Networks**: 2D & 3D CNNs for spatial and temporal gesture analysis.
- **GPT API**: Integrated for prompt-based gesture recognition.
- **Tkinter**: GUI for real-time gesture visualization.

## Challenges and Solutions
- **Challenge**: Handling both static and dynamic gestures simultaneously.
  - **Solution**: Developed a merged solution combining static and dynamic models seamlessly.
- **Challenge**: Noise and motion interference during gesture detection.
  - **Solution**: Applied robust preprocessing and background noise cancellation.

## Future Work
1. Enhance model accuracy with more extensive datasets.
2. Implement additional gesture categories for broader application.
3. Refine GUI for improved user experience.
4. Optimize models for faster predictions in resource-constrained environments.

## How to Use
1. **Setup**:
   - Install required hardware (3D LiDAR sensor) and software dependencies.
   - Ensure the data pipeline is connected for real-time gesture data collection.
2. **Run Models**:
   - Execute the appropriate approach for the use case (GestureKit, 3D CNN, or Merged Solution).
3. **Visualize Results**:
   - Use the Tkinter GUI for real-time gesture display and prediction accuracy.



