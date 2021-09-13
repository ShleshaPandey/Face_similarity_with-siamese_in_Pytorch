# Face_similarity_with-siamese_in_Pytorch
Face similarity with siamese network usinh Pytorch
The code uses AT&T dataset along with nine new face-folders to train the neural networks. The 9 new faces-folders included belongs to different celebrities from India and abroad. A ('unknown') folder containing One picture for each celebrity is created.
After training of the network an image-features' file is created which also contains the label names. The image-feature data is then trained and tested on a classifier to identify the correct label names. The trained claddifier is used to identify the Name of the person(s) whose picture is kept unknown-folder.
