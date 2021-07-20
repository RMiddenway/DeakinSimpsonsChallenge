# DeakinSimpsonsChallenge

As part of the Deakin Simpsons Challenge, my team and I built a convolutional neural network with the goal of labeling images containing Simpsons characters.

## remove_duplicates.ipynb / DataCleaning.ipynb
As part of the data preparation, i wrote a simple script to identify duplicate or near-duplicate images using the wavelet hash function of the imagehash library (https://pypi.org/project/ImageHash/). Each image was converted to a hash, which was then compared with other images in the same class. Similar images were saved into a csv for removal.

## CheckModel.ipynb
This notebook was used to investigate the results of promising models. Incorrect predictions were displayed in order to gain insights as to what might be holding our model back. Graphs were also plotted of class size vs model performance in order to gauge the effectiveness of our dataset augmentation.
