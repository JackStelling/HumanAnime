Hi there,

The code in the 'HumanAnime.ipynb' implementing cycleGAN isn't designed to be ran in a linear fashion. 
The code explains where I've tweaked image size and batch numbers in the image_dataset_from_directory 
functions then re ran code blocks below. I have however included the model checkpoint weights from each
of the runs (Run 1 to Run 7) which can be inserted into the predicting function below the training code.
The cycleGAN model code blocks will need to be executed first as only the weights are saved not the full
architecture due to size limitations.

If you want to use the model to make a prediction you will have to save a test jpg inside another directory
and use the image_dataset_from_directory command as it exists at the bottom of the document. If you have any
issues generating the results please get in touch at j.stelling2@ncl.ac.uk.  


Enjoy,
Jack.  