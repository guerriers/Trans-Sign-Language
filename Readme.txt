1. ติดตั้ง Library 

Library Version(Recommend)
	1. Python – 3.8.10 
	2. OpenCV – 4.6
	3. MediaPipe – 0.8.7
	4. Tensorflow – 2.4.0
	5. Numpy – 1.19.7
2. Run File gesture_detection.python 


mp_hand_gesture
	- variables = เป็น Folders ที่เก็บตัวแปรของ Metrix ต่าง ๆ ในรูปของตัวอักษร
	- keras_metadata = เป็นไฟล์ที่เก็บ data จาก keras เกี่ยวกับ Module ไว้ เป็นไฟล์ที่ถูกเรียกใช้งานโดย tensorflow
	- saved_model = เป็นตัวที่เก็บ Model ไว้และถูกเรียกใช้โดย Tensorflow
data.pickle = เป็นไฟล์ที่เก็บข้อมูลที่ถูกเรียกใช้งานผ่าน Module เมื่อรันโปรแกรม
gesture.names = เป็นไฟล์เก็บชื่อของความหมายที่แปล 