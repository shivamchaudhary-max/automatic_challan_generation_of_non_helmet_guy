# automatic_challan_generation_of_non_helmet_guy
Our objective is to generate the challan of a person who is not wearing an helmet.
i have use yolo v5 detecting algo for detection and use pytesseract for number plate reading.
i have used transfer learning and train 348 images with 500 epocs with batch size 16 for good accuracy. i have use four classes ie: helmet,non helmet,bike,number plate.
precision of all classes is.99 and recall is .99 and map@.95 is .83 .
in our model there are 224 layers and 706200 parameters.
