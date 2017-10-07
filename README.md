# HandwritingRecognition
![screen shot 2017-10-06 at 9 49 07 pm](https://user-images.githubusercontent.com/21322866/31304830-3c3ae17e-aae0-11e7-9b2c-635a7e7c94e9.png)

# Usage
Image data should be an array of size 784(28x28). Each array element should be an integer between 0 and 255. Use draw() to draw the image. Use guess() to predict what number the input array represents. 

# Issues
Handwriting recognition only works for test set, but fails for my own handwriting. Normalization is required before peocessing the input to solve this issue.

# What's New
The accuracy of the recognition is about 80% for both distance/angle implementation. Still trying to find a way to combine the two methods to increase the accuracy...
