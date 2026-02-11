# sand-mining-detection-pof
The major purpose of this project is to design a state-of-the-art deep learning model and implement it within an application framework to produce a highly accurate, real-time sand mining monitoring system for the Vietnamese Mekong Delta

# Objectives
a.	Data Acquisition and Annotation: Compile a high-resolution, spatially focused collection comprising over 1,000 photos of sand mining boats and related operations in the VMD with Google Earth Pro (high-resolution optical imaging).
b.	Model Development: Train and optimise a deep learning model for precise, multi-class identification of sand mining boats including the BC and STB and associated infrastructure.
c.	Performance Evaluation: Use evaluation metrics like accuracy, recall, F1-score, and mean average precision (mAP) to see how well the model works.
d.	Deployment and Monitoring: Create an experimental monitoring application to showcase the model's real-time capabilities to follow the temporal and spatial dynamics of sand mining activities in the area.

# Data Collection
The main source of data will be high-resolution optical satellite photos from Google Earth Pro that focus on well-known sand mining grids around the Mekong River. Using high-resolution images will make the details of the vessels clearer and make it easier to classify them than using the lower- resolution Synthetic Aperture Radar (SAR) images used in earlier studies. More than 2,000 pictures will be taken at active moments to show how the seasons change.

# Data Annotation
We will use label-studio and roboflow to manually design bounding boxes. These boxes will be divided into three groups: Barge with Crane (BC), Sand Transport Boat (STB), and Cluster of boats
