# ActivityTransformer
AcT: Activity Transformer for Motion and Floor Change Detection in Indoor Localization.

#Introduction: 
In this paper, we introduce a new neural model for human activity recognition (HAR) in indoor positioning optimization, called the AcT (short for Activity Transformer) model. The model is a combination of Convolutional Neural Networks (CNNs) and Transformer (Multi-Head Attention) architecture. The AcT model is designed to detect and classify human activities and floor changes using three-axis accelerometer data. The model has output classes for motion, upper floor, lower floor, and static for indoor localization. 

The transformer is particularly important for HAR because it can effectively capture long-range dependencies in sequential data. Human activities often involve complex sequences of movements that can span multiple time steps. The attention mechanism in transformers allows the model to attend to different parts of the input sequence, allowing it to effectively capture these long-range dependencies.

The AcT model can be particularly useful for indoor positioning and localization, as it can accurately detect motion and floor changes in multi-floor buildings. By leveraging the strengths of both CNNs and transformers, the model can effectively capture both spatial and contextual information, leading to improved accuracy in motion and floor detection. Additionally, the AcT model can help to stabilize distance measurements in static mode by filtering out noise and interfering signals.

The novelty of the proposed AcT model lies in the use of a combination of convolutional and transformer layers for human activity recognition in indoor positioning optimization. The model is able to extract meaningful features from the sensor data using convolutional layers and attend to different parts of the input sequence using Multi-Head Attention layers, which allows it to capture complex patterns in the data. The use of transformer layers in the model also allows for better generalization and scalability, as the model can be trained on large datasets with varying input lengths.

The paper presents the results of experiments conducted on five datasets, including a custom wearable accelerometer raw dataset and four standard datasets, with accuracies ranging from 94.45% to 98.26%. The AcT model comprises an encoder, a decoder, and an output layer, with convolutional layers followed by Multi-Head Attention layers for both the encoder and decoder. The output layer consists of a Global Average Pooling layer followed by a Dense layer with softmax activation, which generates the final probability distribution over the output classes.

Overall, the paper presents a novel neural model that outperforms existing techniques for HAR, with potential applications in indoor positioning optimization. The AcT model represents a promising approach to human activity recognition in indoor positioning optimization, with its ability to accurately detect human activities and floor changes, improve distance measurements, and effectively capture long-range dependencies in sequential data.

