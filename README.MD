python install

pip3 install numpy
pip3 install opencv-python

        EDIT (13)
#net = cv2.dnn.readNetFromCaffe("./MobileNetSSD/MobileNetSSD.prototxt","./MobileNetSSD/MobileNetSSD.caffemodel")
TO 
#net = cv2.dnn.readNetFromCaffe("./MobileNetSSD.prototxt","./MobileNetSSD.caffemodel")
