## MxFeedbackReciever
This module can be used to recieve the feedback the user submits via the normal Mendix Feedback widget inside a Mendix app instead of the Sprintr.

## Features
- Recieve Mx Feedback inside your app
- Download the images
- Works with old and newer feedback widgets.

## Usage
- Set the correct security settings for the module
- Add SNIP_FeedbackOverview to a page
- Change the feedback widget fields in the Advanced tab:
   -> App ID change to: feedbackreciever
   -> Feedback server location change to: http://localhost:8080/ to test or your actual environment location where you wish to recieve the feedback. Make sure to end with a slash at the end of the url.

## Issues, suggestions and feature requests
https://github.com/hunter-koppen/MxFeedbackReciever/issues