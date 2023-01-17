# human-detector

# Install requirements
```
pip3 install -r requirements.txt
```

# human-detector cmd help
```
python3 main.py -h
usage: main.py [-h] [-v VIDEO] [-i IMAGE] [-c CAMERA] [-o OUTPUT]

options:
  -h, --help            show this help message and exit
  -v VIDEO, --video VIDEO
                        path to Video File
  -i IMAGE, --image IMAGE
                        path to Image File
  -c CAMERA, --camera CAMERA
                        Set true if you want to use the camera.
  -o OUTPUT, --output OUTPUT
                        path to optional output video file

```

# human detector via webcam
```
python3 main.py -c true -o ./video-output
```
