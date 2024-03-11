Road Crack Detection

This project aims to develop a computer vision system for automatically detecting and classifying various types of road cracks. This system can be used to improve road maintenance efficiency and safety by enabling faster and more objective identification of road damage.
This project utilizes the YOLOv8m deep learning model. The "m" variant signifies the smaller and faster version of the YOLOv8 model.

Dataset Classes:

The system is trained to recognize four critical road defect categories:

1. Crocodile Cracks: These wide, alligator-like cracks indicate severe pavement distress and require immediate repair.
2. Longitudinal Cracks: Cracks running parallel to the direction of traffic flow, often caused by fatigue or shrinkage in the asphalt.
3. Potholes: Circular depressions in the road surface that pose a hazard to vehicles and can worsen if left unattended.
4. Transverse Cracks: Cracks running perpendicular to the traffic flow, typically caused by traffic loading or environmental factors.

Datasets:

To train the YOLOv8m model effectively, the project leverages two publicly available road crack datasets:
1. Roboflow -  https://universe.roboflow.com/road-crack-project/road-crack-detection-combined-dataset
2. Roboflow - https://universe.roboflow.com/search?q=class%3Ahelp


Results:

                 Class     Images  Instances      Box(P          R      mAP50  mAP50-95): 100% 6/6 [00:06<00:00,  1.03s/it]
                   all         82        248      0.633      0.589       0.61      0.309
             Crocodile         82        103       0.77      0.495      0.658      0.341
          Longitudinal         82         71      0.529      0.549      0.484      0.171
               Pothole         82         25      0.783       0.68      0.752      0.515
            Transverse         82         49       0.45      0.633      0.546      0.211
