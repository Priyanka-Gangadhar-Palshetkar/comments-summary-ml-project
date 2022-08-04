# comments-summary-ml-project

## Project Summary

The goal of this model is to provide a summary of comment threads for any given Youtube video in the following formats:

* Paragraph highlighting the key points - "actual summary"
* Word cloud of reactions on the video

## Approach

* In this project, I will be using [Youtube API V3](https://developers.google.com/youtube/v3) to fetch all comment threads for any given youtube video id.

## How to use

1. Download all the dependencies by running the following pip command in your terminal

    ```python
    pip install -r requirements.txt
    ```

2. Create a project on Google cloud console and enable Youtube API V3 for your project. Follow instructions [here.](https://console.developers.google.com/apis/api/youtube.googleapis.com/overview)

3. Change the Youtube API key in config.py with your project's API key. Please find the details to generate the API key [here.](https://developers.google.com/youtube/registering_an_application)

### Libraries used

1. [python-youtube](https://github.com/sns-sdks/python-youtube) - to interact with Youtube API
2. [requests](https://github.com/psf/requests) - to create rest calls to fetch the comments