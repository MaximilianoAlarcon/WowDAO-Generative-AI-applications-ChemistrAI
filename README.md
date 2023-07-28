<h1 align="center">
<b>ChemistrAI</b>
<img height="30em" width="30em" src="icono chemistrai.png" />
</h1>

<h2 align="left">
<b>Context</b>
</h2>

To this day, there are years of documents on chemical formulas scanned but not automatically searchable for specific chemical representations (because they are written on paper and with the skeletal formula).

Automated recognition of optical chemical structures, with the help of machine learning, could speed up research and development efforts. Existing tools produce 90% accuracy, but only under optimal conditions. Historical sources often have some level of image corruption, which reduces performance to near zero. In these cases, time-consuming manual labor is required to reliably convert the scanned images of the chemical structure into a machine-readable format.

Tools to curate the chemical literature would be a significant benefit to researchers. This project aims to help chemists broaden access to collective chemical research. In turn, this would accelerate research and development efforts in many key fields by avoiding duplication of previously published chemistries and identifying novel trends by mining large data sets.

<h3 align="left">
<b>Project Description</b>
</h3>

This translation process is known as Optical Chemical Structure Recognition (OCSR). Today, we are looking back on nearly three decades of development in this demanding research field. Most OCSR methods follow a rule-based approach where the key step of vectorization of the depiction is followed by the interpretation of vectors and nodes as bonds and atoms. Opposed to that, some of the latest approaches are based on deep neural networks (DNN) and this, is based on CNN and RNN combined as one generative model

<h1 align="left">
<b>Project Highlights</b>
</h1>

* The move to open-access, high-quality scientific information systems creates a demand for automatic curation of knowledge from the printed scientific literature. In chemistry, this includes the translation of images of chemical structures into a machine-readable format, which is one of many steps towards the development of more complete curation systems.

* Recent developments in hardware and Deep Neural Networks (DNNs) in machine learning led to outstanding achievements in image recognition technologies. With the cost of the hardware for machine learning getting lower and the accessibility of open machine learning libraries such as TensorFlow, Pytorch, and Caffe, barriers to the implementation of machine learning-based chemical image recognition systems were lowered.

* If characters are resolved with a high confidence level, they are removed from the image. Then, the image is thinned and crossing points and bending points are identified. The remaining elements are divided into lines and curves. After a bond recognition step, the elements are grouped and the “most suitable combination” is determined. Then, the remaining characters are resolved by using a custom OCR engine. According to the authors, ChemistrAI has the advantage of dealing with characters in labels that touch the lines in the structure diagram.

<h1 align="left">
<b>Encoder (Neural Network)</b>
</h1>
<img src="Encoder - Neural Network.png" />

<h1 align="left">
<b>Decoder (Neural Network)</b>
</h1>
<img src="Decoder - Neural Network.png" />
