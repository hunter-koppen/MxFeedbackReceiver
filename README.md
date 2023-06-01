## MxFeedbackreceiver
This module can be used to receive the feedback the user submits via the normal Mendix Feedback widget inside a Mendix app instead of the Sprintr.

## Features
- Receive the input from the Mx Feedback widget inside your own app
- Download the images
- Works with old and newer feedback widgets.

## Dependencies
- Community Commons Module

## Usage
- Set the correct security settings for the module
- Add SNIP_FeedbackOverview to a page
- Change the following Mx feedback widget fields in the Advanced tab (usually found in the layout):
   -> App ID change to: "feedbackreceiver"
   -> Feedback server location change to: http://localhost:8080/ to test it locally or your actual environment location (e.g. https://myapp.mendixcloud.com/) where you wish to receive the feedback. Make sure to end with a slash at the end of the url.

## Issues, suggestions and feature requests
https://github.com/hunter-koppen/MxFeedbackreceiver/issues