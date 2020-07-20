# chest-xray-classifier
This code is  based on the week one homework assignment of the brilliant deep learning for medicine course on coursera found here: https://www.coursera.org/specializations/ai-for-medicine
The purpose of this code  is to provide an example of training and evaluating the model on the entire 40+Gb dataset on  a local machine using Tensorflow 2.2. This means making 
changes such as switching the function keras.backend.gradients() used for generating heatmaps and replacing it with tensorflows GradientTape() in order to avoid the "tf.gradients 
is not supported when eager execution is enabled. Use tf.GradientTape instead." error.  Also other small personal changes are spread throughout he code which separate it from the 
assignment given on coursera which may make it interesting to those interested in seeing other implementations.  The data needed to run this notebook can be found here: 
https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/36938765345. All that is need to run the notebook is to provide directory paths to the data inside the constants cell.
