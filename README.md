

# Abstract
## Thesis submitted for Council of Scientific Students' Associations

Recently a special branch of Machine Learning, a model based on living organic systems called Deep Neural Networks overtakes previous paradigm of algorithmic problem solving. 
It gained larger attention when better results were achieved than task-specific, handcrafted models in feature extraction. 
The reason behind its success is their scalability: the latest architectures are able to exploit the capacity of cutting-edge GPU hardwares since the abstraction of the data are accomplished by succeeding neural nodes performing elementary operations which can be easily paralellized.

It is of the utmost importance to understand the main concept of such networks to contribute to the breakthroughs of the fourth industrial revolution. 
To this purpose, building a framework from the base unit blocks of the latest models is the best introduction to Machine Learning. 
In my research I have disassembled black-box representated networks to the very basic, intuitive level and reorganized it in O.O. manner where each neural layer is treated as an entity derived from a common ancestor, therefore information flow and processes of the system are easily traced. 
Current implementations are based on the principals of the components used by networks built for ImageNet classification, such as Convolutional, ReLU, Max-Pooling, Fully-Connected, Softmax and k-Winner-Takes-All layers.
Furthermore the following training methods and policies were adapted as well: cross validated, minibatch, on-line, $L_p$ regularized and basically Stochastic Gradient Descent training.

For testing the framework, the parameter space of Fully Connected networks was exhaustively explored. 
After train and evaluating sessions - mainly performed on the MNIST and self-acquisited datasets - the re sults were gathered to analyze the performance of different architectures. 
For further investigation the best performing models  were compared to each other to find pros and cons of different capacity, layout and training of networks.

Besides architectural experiments, targeted by many recent researches a non-trivial task of visualizing the inner representation of information, understanding transient activation patterns was studied as well.
Previously mentioned candidate networks were also visualized individually to retrieve information about characteristics of the processes in their Hidden Layer.
My implementation proposes a simplification of the DeConvNet derived from Gradient Ascent, efficient algorithm to reveal patterns recognized by nodes in the hidden layers of Neural Networks, to produce adversarial input samples.


