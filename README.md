Run WS_Product_Recognition.ipynb

Step 1: Logon your Google Colab account

Step 2: create dataset folder 
  Under /content, right-click, then select "New folder" and type "dataet".

Step 3: Upload the collected images and the annotations.json.

Step 4: Click "Runtime" on the main menu, then select "Run all", then run model training, validation, testing and save the model in Pytorch format.

 * start to augment all images and split into train, test and validation. 
 * create an annotation.json on /content/train/test/val subset.
 * make model training and save faster RCNN models into /content/trained_models.

Step 5: go to the last section, load the trained model (e.g. /content/trained_models/fasterrcnn_resnet50_epoch_3.pth), we can see the detection results.
