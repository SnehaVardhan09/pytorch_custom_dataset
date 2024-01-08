# pytorch_custom_dataset
find a dataset, turn into numbers, build a model to find patterns in those numbers on custom dataset 

PyTorch includes many existing functions to load in various custom datasets in TorchText, TorchVision, TorchAudio, TorchRec

0. Importing pytorch and setting up device-agnostic code 
1. Get data
2. Become one with the data(Data preparation)
   whats inspecting the data?
   Before starting building a model, its important to knw what data you're working with.
   Here we have Road Mark Detection.
   The goal will be to take this data storage structure and turn it into a dataset usable with PyTorch.
   Writing a small helper function to walk through each of the subdirectories and count the files present "os.walk()"
 
3. Transforming data
   load our image data into pytorch
   we nned to 1. Turn it into tensor => 2. Turn it into a torch.utils.data.Dataset and subsequently a torch.utils.data.DataLoader, we'll call these Dataset and DataLoader for 
   short.
   





4. Loading image data with a custoom dataset
5. other forms of transforms
7. Model 0: TinyVGG without data augmentation
8. Exploring loss curves
9. Model 1: TinyVGG without data augmentation
10.Compare model results
11.Making a prediction on a custom image

