## MxFeedbackreceiver
This module can be used to receive the feedback the user submits via the normal Mendix Feedback widget inside a Mendix app instead of the Sprintr.

## Features
- receive Mx Feedback inside your app
- Download the images
- Works with old and newer feedback widgets.

## Dependencies
- CommunityCommons Module

## Usage
- Set the correct security settings for the module
- Add SNIP_FeedbackOverview to a page
- Change the feedback widget fields in the Advanced tab:
   -> App ID change to: feedbackreceiver
   -> Feedback server location change to: http://localhost:8080/ to test or your actual environment location where you wish to receive the feedback. Make sure to end with a slash at the end of the url.

## Issues, suggestions and feature requests
https://github.com/hunter-koppen/MxFeedbackreceiver/issues