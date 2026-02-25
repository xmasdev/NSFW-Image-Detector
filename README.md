# Image Classification Project
Multi class image classification project, transfer learning using pretrained InceptionV3. 

## Dataset
The dataset used for training the models can be found at [Hugging Face Datasets](https://huggingface.co/datasets/deepghs/image_classification).

## Status
Currently discontinued, however working correctly with a test_accuracy of about 85%.

## Usage
Make sure you have the required modules installed modules installed.
``` bash
pip install numpy, tensorflow, keras
```
Then run the `main.py` file with the root directory structure as
```
| - data
|     | - train
|     | - validation
|     | - test
| - main.py
| - predict_image.py
```
This will create the required model file. <br>
To run the model, run the `predict_image.py` after editing the `image_src` variable inside.

## License
This project is licensed under the terms of the MIT license.

