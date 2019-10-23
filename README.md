# Optical flow samples

From https://github.com/npinto/opencv/blob/master/samples/python2/opt_flow.py

Modified
- Add astype(int) cast
- Use `cv2.VideoCapture(fn)` instead of `video.create_capture(fn)`
- Add braces for print
- Add ` cam.release()`
