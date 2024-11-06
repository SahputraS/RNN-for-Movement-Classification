# HDA-Project
Human Data Analytics Project A.Y.23/24

This project explores the effectiveness of three neural network architectures
- Solo RNN
- Convolutional-RNN (CRNN)
- Convolutional-Bidirectional-RNN (CBR)
to classify human activity such as walking, ascending and descending stairs. 

The dataset, sourced from the IUWDS study, includes time series data collected from 32 adults (13 men and 19 women) wearing ActiGraph GT3X+ accelerometers placed on the left and right ankles, left hip, and left wrist. 
The accelerometers were recorded at a frequency of 100 Hz during various activities, including a 1 km walking trail with level ground and stairs and city and highway driving. 

Without prior feature engineering, all models achieved accurate classifications. 
The CBR model excelled by balancing high accuracy (Macro F1 Score of 0.99) and efficient processing time. 
This method is suitable for real-time applications on limited-resource devices.
