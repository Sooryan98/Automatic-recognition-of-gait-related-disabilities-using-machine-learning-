# Automatic-recognition-of-gait-related-disabilities-using-machine-learning-
Title: GaitDisabilityML

Description:
GaitDisabilityML represents an open-source initiative dedicated to the automated identification of gait-related disabilities through the application of advanced machine learning methodologies. The project employs a diverse array of algorithms, including k-Nearest Neighbors (kNN), Dense Neural Networks (DNN), Long Short-Term Memory (LSTM), and others, with the overarching goal of contributing to the progression of assistive technologies. This contribution seeks to furnish a robust and precise solution for the identification and comprehension of gait impairments.

Key Features:
1. **Data Acquisition:** Employing OpenCV and MediaPipe, the project extracts pertinent information from a recorded video sourced from an Android phone. This process, centered on simplicity, ensures the efficient collection of data vital for gait analysis.

2. **Data Generation:** The project incorporates a systematic data generation mechanism meticulously designed to encapsulate 13 features. This process facilitates a comprehensive analysis of gait patterns, encompassing metrics such as average arm angle, arm swing frequency, and other salient characteristics crucial for a nuanced understanding of gait-related disabilities.

3. **MediaPipe Pose Estimation:** The integration of MediaPipe Pose Estimation is instrumental in extracting real-time data regarding joint positions within the body. This augmentation significantly enhances the precision and granularity of gait analysis.

4. **TensorFlow Models:** The project leverages TensorFlow models in conjunction with MediaPipe, refining gait recognition by enabling precise node position calculations. This integration further fortifies the model's capability to detect and categorize gait-related disabilities with heightened accuracy.

5. **Machine Learning Models:** The endeavor encompasses the exploration and implementation of various machine learning models, such as kNN, DNN, LSTM, and other state-of-the-art algorithms. These models are intricately designed to scrutinize gait patterns and discern disabilities with a high degree of efficacy.

GaitDisabilityML distinguishes itself from analogous research, particularly the referenced paper [here](https://link.springer.com/article/10.1007/s11042-011-0786-1), through the adoption of a methodologically divergent approach. Notably, this initiative emphasizes accessibility, utilizing commonplace technology such as phone-recorded videos and MediaPipe Pose Estimation in lieu of specialized equipment like IR retroreflective tags and motion capture cameras. The chosen methodology not only enhances accessibility but also ensures compatibility with widely available resources. Importantly, the features employed in the referenced paper are meticulously replicated in this project, facilitating a rigorous and meaningful comparative analysis.

