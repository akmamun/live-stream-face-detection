## Live Streaming and Face Detection with Flask
 ```python
 pip install requirements.txt
```
### Run Server
  ```python
  python app.py
```
##### cv2.VideoCapture(0) Zero '0' meam webcam open or instead of zero put rtsp link
 ```python
 rtsp://username:password@camera_ip_address:554/user=username_password='password'_channel=channel_number_stream=0.sdp  
 ```
#####  Example rtsp link
 ```python
cv2.VideoCapture('rtsp://mamun:123456@101.134.16.117:554/user=mamun_password=123456_channel=1_stream=0.sdp')
 ```