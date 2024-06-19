# CNN-Vs-QCNN
Quantum Convolution Neural Network

Classical Convolutional Neural Networks
![image](https://github.com/SevdanurGENC/CNN-Vs-QCNN/assets/5441882/7b156662-bada-4fe4-9cc8-a6e9ad8e7f51)

A simple example of four qubit QCNN can be seen below.
![image](https://github.com/SevdanurGENC/CNN-Vs-QCNN/assets/5441882/10d09c95-5af6-4190-83eb-5e2462bb227e)

We create a function for our QCNN, which will contain three sets of alternating convolutional and pooling layers, which can be seen in the schematic below. Through the use of the pooling layers, we thus reduce the dimensionality of our QCNN from eight qubits to one. To classify our image dataset of horizontal and vertical lines, we measure the expectation value of the Pauli Z operator of the final qubit. Based on the obtained value being +1 or -1, we can conclude that the input image contained either a horizontal or vertical line.
![image](https://github.com/SevdanurGENC/CNN-Vs-QCNN/assets/5441882/e816bcf2-84a1-4a2c-a25c-110555ca79d8)

![image](https://github.com/SevdanurGENC/CNN-Vs-QCNN/assets/5441882/6418b738-9ea7-46b0-9981-efca240db021)

![image](https://github.com/SevdanurGENC/CNN-Vs-QCNN/assets/5441882/00017d27-f853-47d6-9aa9-d2bc5db013db)

![image](https://github.com/SevdanurGENC/CNN-Vs-QCNN/assets/5441882/62829711-c542-493e-9441-27193e375f31)

