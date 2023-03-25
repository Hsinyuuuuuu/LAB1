# LAB1
Detect Pneumonia from chest X-Ray images
First, we used ImageFolder to have our x-ray photos. Used transforms to do augmentation at the same time.
Then uesd DataLoader to read our data.
Used Pytorch pretrained model ResNet 50.
Trained 15 epochs, batch size 64, learning rate 10^-5, optimizer Adam.
Plot accuracy figure, F1-score and confusion matrix heatmap.
