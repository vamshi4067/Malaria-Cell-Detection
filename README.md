Description of the dataset:

The dataset is originated from NIH website which is a repository for all the health datasets used for health analytics. The size of the dataset is 334MB and the dataset consists of two folders Parasitized and Uninfected with 13,780 images in each folder where Parasitized folder consists of images of all the human cells which are affected by malaria and Un-infected folder consists of the images of human cells which are not affected by the malaria. This dataset was collected and analyzed with the goal to detect the
cells effected from malaria, so that the infected person can be informed at the initial stages of the infection before it turns endemic.

Problem:

By looking at the images in the dataset a human can easily say which cells are affected by malaria and which are not affected, but it would be a tiresome job for a human to check all the endemic cases. So, in order to automate this process we need to find a best modeling techniques in deep learning to correctly classify the new or unseen image into parasitized and uninfected categories. So, this is classification problem with an output of only two classes.

Proposed Architectures:

Since we are working with an image dataset using CNN for classification would achieve better results. However to find the optimal values we need tune hyper-parameters of the CNN to output us accurate results and for building a robust model. So, we tried to use few of the pre-trained models like resnet-18 which had its parameters pre-trained and wanted to see if that would make our the prediction more accurate.