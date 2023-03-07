
 The German Traffic Sign Benchmark is a multi-class, single-image classification challenge held at the International Joint Conference on Neural Networks (IJCNN) 2011.
- Single-image, multi-class classification problem
- More than 40 classes
- More than 50,000 images in total
- Large, lifelike database

Using the InceptionV3 pre-trained model, I converted the individual layers of the model into trainable layers, therefore in total there were 
over 21 million trainable parameters and ultimately produced a validation accuracy of 97%+ and a test accuracy of ~98%+. From carrying out this procedure, I was able to deduce that pre-trained models such as the Inception V3 model are vastly superior than custom made models with regards to epoch time and producing high accuracy values.
