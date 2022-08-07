# Pneumonia Detection using Convolutional Neural Networks

## What is Pneumonia?
Pneumonia is a form of an acute respiratory infection that affects the lungs. The lungs are made up of small sacs called alveoli, which fill with air when a healthy person breathes. When an individual has pneumonia, the alveoli are filled with pus and fluid, which makes breathing painful and limits oxygen intake.

Pneumonia is the single largest infectious cause of death in children worldwide. Pneumonia killed 808 694 children under the age of 5 in 2017, accounting for 15% of all deaths of children under five years old. Pneumonia affects children and families everywhere but is most prevalent in South Asia and sub-Saharan Africa.

## Project Overview
With these facts serving as an inspiration I had started working on my project:

To start off with I needed to figure out where I can build and run the code as my systems specs were not sufficient to handle the amount of computational power it takes to build a model so I used Google’s Colab. Colab allows you to write and execute Python in your browser, with

Zero configuration required
Free access to GPUs
Easy sharing
Whether you’re a student, a data scientist or an AI researcher, Colab can make your work easier.

Note: Need API

In the below code I have also mentioned how to access the dataset from Kaggle but the important things to note are:

Have your API key file i.e. ‘kaggle.json’ ready
With this method, every time the runtime resets in google collab you will lose all your files and the generated model so once done always download your model file and after every reset remember to re-import the dataset
## What Am I trying to Achieve?
When you submit an X-Ray Image of a 5-year-old kid’s chest, the algorithm should be able to predict with high accuracy, if the patient has Pneumonia.
## The Code
I have used the Chest X-Ray Images (Pneumonia) dataset by Paul Mooney as the data was already conveniently split into the train, test, and val:
Train -contains the training data/images for teaching our model.
Val — contains images that we will use to validate our model. The purpose of this data set is to prevent our model from overfitting. Overfitting happens when a model learns the detail and noise in the training data to the extent that it negatively impacts the performance of the model on new data. This means that the noise or random fluctuations in the training data is picked up and learned as concepts by the model. The problem is that these concepts do not apply to new data and negatively impact the model’s ability to generalize.
Test — this contains the data that we use to test the model once it has learned the relationships between the images and their label (Pneumonia/Not-Pneumonia)

## Conclusion
It is fairly easy for any developer with decent programming skills to create a Machine Learning models which could be useful to millions of people.

Much better results have been achieved by professionals out there. As a beginner, I was able to achieve an accuracy of 89%, which is clearly not bad. But in order to be used in the real world, by millions of people, 89% accuracy means it will misdiagnose roughly 1,00,000 cases.


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Pneumonia Detection using Convolutional Neural Networks.

```bash
pip install Pneumonia Detection using Convolutional Neural Networks
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
