To use the handwritten digit recognition neural network you must do the following:
1. Navigate to this directory "dl4j-examples/dl4j-examples/src/main/java/org/deeplearning4j/examples/dataexamples/"
2. In the directory search for and run the program "MnistImagePipelineExampleSave". This will create, train, and save the neural network.
3. If not already done beforehand, prepare images of handwritten digits you plan to use with the network.
   Said images need to be 28 x 28 pixels with white text on a black background.
4. Search for and run the program "MnistImagePipelineLoadChooser". When prompted, search for an image you wish to use and the program will
   use the trained network to predict what number the image is supposed to be.
