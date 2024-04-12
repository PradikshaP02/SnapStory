Every day, we encounter a large number of images from various sources such as the internet, news articles, document diagrams and advertisements. These sources contain images that viewers would have to interpret themselves. Most images do not have a description, but the human can largely understand them without their detailed captions. However, machines need to interpret some form of image captions if humans need automatic image captions from it. Image captioning is important for many reasons. Captions for every image on the internet can lead to faster and descriptively accurate images searches and indexing.

The goal is to use computer vision and deep learning to identify the context of an image and annotate it with pertinent captions. It involves using datasets supplied during model training to classify an image with English keywords. The CNN model known as Xception is trained using the imagenet dataset. The extraction of features from images is handled by Xception. The LSTM model, which creates the image description, will be fed these extracted features.
The Transformer is an improvised model architecture that completely relies on an attention mechanism to identify global relationships between input and output, rather than relying on recurrence. The Transformer design may provide new state-of-the-art translation quality results and allows for much more parallelization.


Tools and technology - Keras-Tensorflow, Streamlit and Jupyter notebook

Dataset - Flickr8K Dataset with 8000 image 
	      - Each image has 5 captions associated with it

