# Evaluation-of-Uni-and-Bidirectional-RNN

This work aims to provide a comprehensive evaluation of unidirectional and bidirectional recurrent neural networks for sequence prediction. Through a comprehensive evaluation, this work highlights the strengths and weaknesses of each RNN architecture in terms of prediction accuracy and computational efficiency. We test four types of RNN cells within the encoder and decoder networks, including unidirectional Long Short-Term Memory (Uni-LSTM), bidirectional Long Short-Term Memory (Bi-LSTM), unidirectional Gated Recurrent Unit (Uni-GRU), and bidirectional Gated Recurrent Unit (Bi-GRU).          

![result](https://github.com/sammyyap98/Evaluation-of-Uni-and-Bidirectional-RNN/assets/87789723/cbe65624-e844-4149-8a07-6c92969f5547)

From the experiment results as shown in the figure above, it can be observed that the Bi-GRU model achieves the highest accuracy of 90.95%, followed by the Bi-LSTM model with 89.33%, the GRU model with 88.63%, and lastly, the LSTM model with 81.90%. The bidirectional models (Bi-LSTM and Bi-GRU) demonstrate better performance in terms of accuracy compared to their unidirectional counterparts (LSTM and GRU). This can be attributed to the way bidirectional models process the input data. They capture information from both past and future time steps, allowing them to understand the context more effectively, leading to improved predictions. In contrast, unidirectional models only process input data from past time steps, limiting their ability to capture future context.


![Table_1](https://github.com/sammyyap98/Evaluation-of-Uni-and-Bidirectional-RNN/assets/87789723/b52c5449-5286-4996-8835-05d20292e72e)

 

![Table_2](https://github.com/sammyyap98/Evaluation-of-Uni-and-Bidirectional-RNN/assets/87789723/4a5adaf4-4b35-45b7-a531-c638a8e75833)
