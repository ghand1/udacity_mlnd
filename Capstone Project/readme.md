
## Udacity Machine Learning Nanodegree Capstone Final Report
#### Deep Learning with MapSwipe Dataset - readme
#### By David Ghan

For this project, I explore the MapSwipe data where users classify satellite images based on varying target variables. The app uses crowd sourcing to classify massive amounts of satellite imagery of rural and developing areas around the world in the hopes that humanitarian aid organizations can better identify vulnerable communities. I chose to specify my project to rural Malawi areas where the purpose was to identify buildings and structures within each image. 

By accessing these images classified by users, I built a deep learning model to automate the process of identifying the target variable in each image. For this task, I use Keras/Tensorflow to explore the dataset and build multiple models to compare performance. Each model is measure according to its accuracy and log loss. More details can be found in the PDF capstone report, outlining my process and steps taken.

In order to access the satellite images, I used [philiptromans'](https://github.com/philiptromans/mapswipe-ml) excellent python code to extract the MapSwipe images needed for the dataset. This code allows for users to specify which MapSwipe projects to extract as well as the number of images to be sorted into train, test and validation files. A Bing Maps API key is required but easy to obtain from [here](https://msdn.microsoft.com/en-us/library/ff428642.aspx). 

Require libraries include:
* keras
* matplotlib
* numpy
* pandas
* cv2
* PIL
* glob
* skimage
* sklearn





```python

```
