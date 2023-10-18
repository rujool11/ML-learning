### **Food101 Data Image Classification using Transfer Learning**

**Data Used** : Food101 Dataset, 101000 images of 101 different food classes

Model trained using Transfer learning, base model : **EfficientNetv2B0**

Model trained for 8 epochs with new output layer

**Fine tuning** -- 15 layers of base model unfrozen and trained for epochs 9-16, then 25 layers unfrozen and trained for epochs 17-20

Mixed precision training used for faster training

Final Accuracy: Correct Predictions accross **75.54%** of all training data
