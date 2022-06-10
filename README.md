# Realtime Sign Language Detection
Tensorflow 2 image_detection API used to detect sign language words from custom trained model.

## Requirements

For the Tensorflow 2 API setup, please follow instructions in the docs [here](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html#anaconda-python-3-8-optional).

Create virtual env or Docker. Run the following inside the repo to install all dependencies:

```$ pip install -r requirements.txt```

## Usage

Follow instructions in webcam_img_collector to collect own labeled image data for training as per class prediction preferences. In this case, I used South African Sign Language examples "yes", "no", "hello", "I love you", "thanks".

Important to note, the model is trained on images / frames of the video feed. A large part of sign language is very dependent on movements or actions which in effect limits the model vocabulary's scalability.

Train / test images are not included in repo.

## Output

![Alt Text](https://github.com/feeblefruits/realtime_sign_lang_detection/blob/main/readme_assets/ezgif-4-c22322dab9.gif)

## References

Besides the docs mentioned above, the following resources assisted in putting this repo togeter: 

<ul>
  <li>https://github.com/nicknochnack/RealTimeObjectDetection</li>
  <li>https://gilberttanner.com/blog/object-detection-with-tensorflow-2/</li>
</ul>
