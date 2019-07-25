## COSC6368 Final Project
### Binoy Dalal (1794070), Summer 2019
#### Gender classification of blog authors
***

Environment:
* Python 3.6
* Dependencies are present in the file requirements.txt. In order to install the dependencies, run `pip3 install -r requirements.txt`
* It is strongly suggested that the code be run on a system with Nvidia GPU support, as otherwise POS tag generation and tensorflow make take a long time to run
* _Note: Tensorflow-GPU requires CUDA and preferably cuDNN support to run effectively. These libraries need to be installed separately if not already present on the system. Alternatively, one can install the CPU version of tensorflow._

Notebooks:
* `generate_pos_tags_glove.ipynb`: code to generate the glove representations for POS tags
* `visualize_glove_vectors.ipynb`: code to visualize the glove representations for POS tags
* `rnn_pos.ipynb`: code to train a recurrent model on POS embeddings
* `rcnn_model.ipynb`: code to train an RCNN model on the corpus
* `rcnn_balanced_gender.ipynb`: code to train an RCNN model on balanced classes from the corpus
