# Instance Segmentation Model
To train a deep learning model to perform an instance segmentation model. You need to submit each instance labelled with one single colour. You need to submit a video with each instance labelled with one single colour. You need to attach a document explaining the steps, To submit code is your choice.

Step 1: Data Preparation

Gather a labeled dataset with images and instance masks.
Split the dataset into training and validation sets.
Step 2: Choose a Framework and Library

Framework: Use TensorFlow or PyTorch.
Libraries: Utilize TensorFlow Object Detection API or Detectron2 for PyTorch.
Step 3: Select a Model Architecture

Choose from architectures like Mask R-CNN, FCN, or DeepLab.
Pretrained Models: Use COCO-pretrained models for a head start.

Step 4: Model Training

Fine-tune the chosen model on your dataset.
Adjust hyperparameters, learning rate, and optimizer.
Monitor loss, accuracy, and other metrics during training.
Step 5: Evaluation

Use mean Average Precision (mAP) to measure instance segmentation performance.
Calculate frame per second (FPS) to assess inference speed.

Step 6: Hardware Configuration for Inference

Specify the CPU/GPU used for inferencing.
Note the memory and processing power.

