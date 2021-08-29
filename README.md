# Classified Memes and Notes
This project was aimed to classify memes and notes by two approaches, one with CNN and one without CNN.
## Dependencies 
- Python=3.7
- Numpy
- Matplotlib
- Pandas
- h5py
- OpenCv
- Pytorch
- Glob
## Dataset 
Dataset was generated collectively by students, by collecting memes and notes images from various sources. The dataset was split as follows
- 1000 images in training data
- 300 images in validation data
- 300 images in test data
## Approach
### Without CNN
The network architecture of Deep Neural Network was n,6000,2000,1000,500,100,20,1 with learning rate as 0.01, 5 epochs and a batch size of 100. All of this was implemented purely on Numpy.
<br />
![repo24](https://user-images.githubusercontent.com/64823050/131244446-737e5074-0164-499d-8c82-f939f2efa382.png)
### With CNN
The network architecture was as follows: 
<br />
![repo25](https://user-images.githubusercontent.com/64823050/131244511-40ef6345-292a-403f-a864-90b8ba413173.png)
<br />
This was implemented using Pytorch.
<br />
## Result 
