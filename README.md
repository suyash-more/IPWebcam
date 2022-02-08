
# IP Webcam :camera:

<img src = "https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white"/> <img src = "https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white"/>
<hr>

Few References
 - [Flask](https://flask.palletsprojects.com/en/2.0.x/)
 - [OpenCV Documentation](https://docs.opencv.org/4.5.5/)

Install Flask
```sh
> pip install -U Flask
```

Set the app variable 
```sh
> set FLASK_APP=main.py
```
Name the file with the app i.e. in my case **main.py**

Then run the application across your network
```sh
> flask run --host=0.0.0.0 --port=8080
```
Now you have your WebCam of laptop / pc streaming the live feed on 
here.
```sh
> {IP_ADDRESS}:8080
```
**IP_ADDRESS** = ip address of your laptop / pc

Connect both the laptop and your mobile / any other device to the same network.
Open Web browser on the end device and put **`{IP_ADDRESS}:8080`** in the url.


https://user-images.githubusercontent.com/63491387/153026030-1be74686-d740-44b2-9294-0f8cdf1f1a18.mp4



### Njoy....
