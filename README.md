# Reverse Image Search

### Deeplearing based Reverse Image Search using Annoy library

Finding visual content with semantic meaning is a very important task. It has applications in the field of e-commerce(using camera to shop for a similar furniture), recommendation systems (like PinSage @ Pinterest or discover weekly @ Spotify). In this [notebook](./Pytorch_Amul.ipynb), I use Annoy to build a rudimentary Reverse Image search system using deep learning. In this system, a sample image formulates a image query.
You can find some of the results below and a detailed explanation in the accompanying [blog](https://medium.com/@sureshr/reverse-image-search-c4823b99de10).

### Blog link: https://medium.com/@sureshr/reverse-image-search-c4823b99de10

### Experimental Results:

#### Each model is in a column of its own. Query image is the first row the subsequent rows are nearest neighbors for each model
![Usain Bolt](./images/bolt.png)

![Rocket Launch](./images/isro.png)

![Paul Walker](./images/paul.png)


### Ensemble Results:

#### Query image is the first row the subsequent rows are nearest neighbors based on ensemble of all models
![ensemble](./images/ensemble2.png)
