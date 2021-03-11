# Automatic Number Plate Recognition for Non Roman Fonts & Other Scripts
> Won first prize among 917 other competing teams (₹50000 awarded).

### File Description:
1. Data-Images: Contains the images of the cars, number plates and annotations in .txt files
2. Data.ipynb: A notebook demonstrating the process of preparing the .csv files for creating TFRecords.
3. Indian_Number_plates.json: Configuration file which contains image download paths and annotations.
4. test.record & train.record: TFRecords files of testing and training sets respectively
5. test_labels.csv & train_labels.csv: .csv files as required by the generate_tfrecord.py script
6. exported_graph: Contains the inference graph in .pb and .tflite formats which can be used to run inference.
7. label_map.pbtxt: Contains the encodings of the dataset classes which,in this case, is 1: license_plate
8. ssd_mobilenet_v1_pets.config: Training and evaluation pipeline configuration file as needed by TensorFlow Object Detection API
9. test.record & train.record: TFRecords files of testing and training sets respectively
10. test_labels.csv & train_labels.csv: .csv files as required by the generate_tfrecord.py script
11. object_detection: A folder from Tensorflow objection detection API which is required in the same directory as that of the generate_tfrecord.py
