# **Dog Breed Prediction**

![h](https://user-images.githubusercontent.com/96771321/214430950-66cc8641-b309-4de1-8a8f-7a568f69910c.jpg)

## Introduction
The Dog Breed Prediction project utilizes TensorFlow and transfer learning with the Xception model to develop a powerful neural network capable of identifying dog breeds with high accuracy. The project focuses on the top 10 most populated dog breeds from a dataset comprising 120 different breeds.

## Repository Structure

The repository structure include:

```
├── .idea/
├── .streamlit/
├── LICENSE
├── Procfile
├── README.md
├── app.py
├── dog_breed.h5
├── notebook.ipynb
├── requirements.txt
└── setup.sh
```

In this structure:

- `.idea/`: Directory containing configuration files for JetBrains IDEs, such as PyCharm.
- `.streamlit/`: Directory for Streamlit configuration files, if you're using Streamlit for your project.
- `LICENSE`: File containing the license information for your project.
- `Procfile`: File specifying the commands to run your application in a hosting environment, such as Heroku.
- `README.md`: Markdown file with project documentation, instructions, or other relevant information.
- `app.py`: Python file containing the main code for deployment.
- `dog_breed.h5`: Pre-trained model file or model weights.
- `notebook.ipynb`: Jupyter notebook file for exploratory analysis and experiments.
- `requirements.txt`: File listing the required Python libraries and their versions.
- `setup.sh`: Shell script for setting up the project environment or executing necessary setup commands.


## Dataset
The dataset used in this project consists of training and test sets containing images of dogs. Each image is uniquely identified by its filename, and the dataset provides a comprehensive collection of dog breed images for training and evaluation purposes. The data source for this project is available on Kaggle.

## Model
The model employed in this project is the Xception model, a pre-trained deep learning model known for its accuracy and efficiency. By leveraging transfer learning, the model can utilize the knowledge learned from a large dataset to accurately classify the dog breeds in the test set.

## Results
After extensive training and fine-tuning, the model achieves an impressive accuracy of 95.65% on the test set. This performance demonstrates the model's ability to identify intricate patterns and features that differentiate one dog breed from another.

## Deployment
To make the project more accessible and interactive, a deployment site has been created. The Dog Breed Classifier application allows users to upload their own dog images and witness the model's real-time predictions of the respective breed. Visit the deployment site at [https://davidsonity-dogbreed-classifier-app-opihvk.streamlit.app/](https://davidsonity-dogbreed-classifier-app-opihvk.streamlit.app/).

## Additional Resources
For a more detailed understanding of the project's implementation and code, please refer to the notebook available on GitHub: [View Notebook](https://github.com/Davidsonity/DogBreed-Classifier/blob/main/notebook.ipynb).

## Conclusion
The Dog Breed Prediction project demonstrates the power of deep learning and transfer learning in accurately classifying dog breeds. By harnessing the capabilities of TensorFlow and the Xception model, this project achieves remarkable accuracy and showcases the potential of artificial intelligence in image classification tasks.

Stay tuned for more advancements in machine learning and computer vision, as the Dog Breed Prediction project continues to unlock new possibilities in the field of canine breed identification.

## Contribution
Contributions to this project are welcome. If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
