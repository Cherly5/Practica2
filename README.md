Convolutional Neuronal Network
--------------------------------------------------

Description:
We have built a neuronal network that recognizes images and classifies them as follows: ['Emerald', 'Fake_Emerald', 'Fake_Ruby', 'Fake_Turquoise', 'Ruby', 'Turquoise']

Dataset Used:
The dataset we used in our neuronal network consists of 3 different types of gemstones, and each one whether they are real or fake. The following link goes directly to the dataset 
page on Kaggle: 
[kaggle.com/datasets/muhammadmuzamil5500/gemstones]()

Training Phase:
The network works really nicely, achieving more than 90% of accuracy and less than 0.4 loss.

Validation Phase:
During the validation phase, the network achieves more than 0.8 accuracy and less than 0.6 loss .

Test Phase:
However during the test phase we've been having complications due to the database and more specifically the class 'turquoise', which happens to be the first option of the network
when it comes to predicting the class of an unkown image.
We have achieved 93.8% accuracy.
