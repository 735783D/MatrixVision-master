# Jason's Version of Matrix Vision

I got this code from CoderSpace on Youtube found here: https://www.youtube.com/watch?v=fNoQr3q3RVc&list=PLVfwV2MU100ICO1ZMGhir8YFzWIxnHNCb&index=2

For my particular setup I commented certain sections in case anyone would want to be able to just use the Matrix effect on a still frame picture. You can adjust the values backwards to make vertical pictures. I tried this on a picture that was NSFW so it isn't in the project file.

If you want to use the webcam functionality, you need to install a particular package (OpenCV). The problem is that in the video it shows an outdated version of the package. 

This is the correct version for Python 3.7+:
```
pip install opencv-contrib-python
```
You will also need to install 'pygame' and 'numpy' as well, but that part is okay in the video.

If you want more knowledge of how OpenCV works, there is a course on it from FreeCodeCamp.org I just found on YouTube: https://www.youtube.com/watch?v=oXlwWbU8l2o  As of this writing, I haven't gone through it yet. But I will at some point.