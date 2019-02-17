# Image Classifier

## Table of Contents

* [Description](#description)
* [Tools & Dependencies](#tools)
* [Installation](#installation)
* [Contributing](#contributing)
* [License](#license)

## Description

Going forward, AI algorithms will be incorporated into more and more everyday applications. For example, you might want to include an image classifier in a smart phone app. To do this, you'd use a deep learning model trained on hundreds of thousands of images as part of the overall application architecture. A large part of software development in the future will be using these types of models as common parts of applications. 

In this project, I have trained an image classifier to recognize different species of flowers. You can imagine using something like this in a phone app that tells you the name of the flower your camera is looking at.

I have used [this dataset](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html) of 102 flower categories, and you can see a few examples below. 

<img src='assets/Flowers.png' width=500px>

The project is broken down into multiple steps:

* Load and preprocess the image dataset
* Train the image classifier on the dataset
* Use the trained classifier to predict image content

I have implement this application in Python. This application can be trained on any set of labeled images, here my network is learning about flowers. This is a command line application, which could be turned into a mobile app or website.

## Tools & Dependencies

The data in this repository comes from [this dataset](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html).

Download the data and store it in the `/flower_data/` folder.

Analysis has been performed in the [Jupyter Notebook](http://jupyter.org/), using Python 3.x.  

## Installation

To run this project:
  
1. With python 3.x installed, create a virtual environment and activate it as shown:
  
```shell
  virtualenv -p python3 my_virtualenv
  source my_virtualenv/bin/activate
```
2. Clone this repository into your virtual environment:  

```shell
git clone https://github.com/BarbaraStempien/DL--Image-Classifier.git
```
3. Install project dependencies:  

```shell
pip install -r DL--Image-Classifier/requirements.txt
```
  
4. Open Jupter Notebook, and run the project.

## Contributing

I accept contributions. For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[MIT License](LICENSE)

Copyright (c) 2018 Barbara Stempien

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
