# How Can We Compare Song Audio Files and Classify them?

## Research Question
Since we’ve never worked with audio data or classification of audio data we wanted to try working with data that is structured as such. 
We ask the question: how do the audio features from songs, specifically Spotify Tracks compare to each other? 

Is there a relationship between the some of these features such as tempo correlating with danceability/energy/liveness and if so how are they correlated. Additionally, how can we use these features to cluster songs based on these audio tracks of songs being coverted to numeric features?

## Hypothesis
Certain audio features will be statistically different between the distribution of certain genres. These differences in distributions will allow us to perform Unsupervised Learning on the data to cluster the songs into different groups / listening personas. 

For example, the mean "tempo" of Pop Artists will be higher than that of Ballad Singers since Pop songs tend to be more upbeat and fast. 

If numerical data is extracted from the songs then models can be trained to cluster / classify songs into different groups since there will be enough difference between certain features between certain groups. This approach of comparing audio features between two groups can then be applied to other projects such as comparisons of living beings/objects to classify the two.

## Table of Contents

1. [Overview](#overview)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Further Applications](#further-applications)
5. [Contributors](#contributors)

## Overview

This project consists of the following components:

1. Audio Feature Extraction: We extract audio features on the Top Charting Songs from Spotify's API
2. Model Selection: Performing different Supervised and Unsupervised Learning algorithms
3. Evaluation: We evaluate the supervised model's performance using accuracy, precision, recall, and F1-score metrics.
4. Adaptability: The project is designed to be easily adaptable for other audio classification / clustering tasks.

## Requirements
- Python 3.8+
- librosa
- TensorFlow
- Keras
- NumPy
- pandas
- scikit-learn
- Optional: Cuda (if training on an Nvidia GPU)

## Installation
To install the project and its dependencies, follow these steps:

1. Clone the repository:

```
git clone https://github.com/COGS108/Group_Sp23_The_group_chat
```

2. Change to the project directory:

```
cd Group_Sp23_The_group_chat
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

## Further Applications

This project can be easily adapted to other audio classification tasks, such as:

- Identifying speakers in a conversation
- Detecting emotions in speech
- Recognizing animal sounds or bird calls

To adapt the project, simply prepare your data and follow the usage instructions outlined above.

## Contributors

- [Nate del Rosario](https://natdosan.github.io)
- [Lisa Hwang](https://github.com/lisasunhwang)
- [Mateo Ignacio](https://github.com/mjignacio)
- [Geovaunii D. White](https://github.com/geovaunii)
- [Samuel Piltch](https://github.com/samuelpiltch)

We appreciate all contributions to this project. If you would like to contribute, please open an issue or submit a pull request on the project's GitHub repository.
