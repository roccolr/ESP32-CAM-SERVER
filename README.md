# ESP32-CAM-SERVER-WITH_PYTHON_CLIENT
A simple ESP32 CAM server gets images for a python client that stores the picture in a given path.

The ESP32 I used for this project is the AI THINKER ESP32 CAM, and I used Python3 for the client development.

## HOW TO USE IT

run the script autodataset.py with your path as an arg.

```bash
python3 ~/PATH/WHERE/THE/SCRIPT/IS/STORED/autodataset.py /ABSOLUTE/PATH/FOR/UR/PIC/TO/BE/STORED
```

upload the .ino code on your esp32 cam, and should work like a charm. 
The project is tought as a simple couple of scripts that allows you to take pitures and send them locally to your machine,
in the future I'm planning to extend it to more general purposes. 
