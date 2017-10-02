# HandwritingRecognition
![screen shot 2017-10-02 at 12 50 42 pm](https://user-images.githubusercontent.com/21322866/31096255-5d2fcf98-a770-11e7-9cda-816b8e1a1da0.png)

# Usage
Image data should be an array of size 784(28x28). Each array element should be an integer between 0 and 255. Use draw() to draw the image. Use guess() to predict what number the input array represents. 

# Issues
Handwriting recognition only works for test set, but fails for my own handwriting. Normalization is required before peocessing the input to solve this issue.
