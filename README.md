# Traffic_Surveillance
The goal of the project is to automate the traffic signal
violation detection system and make it easy for the traffic police
department to monitor the traffic

The System consists of two main components -
• Vehicle detection model
• A graphical user interface (GUI)


1) Vehicle Classification
 From the given video footage, moving objects are detected. An
object detection modelYOLOv3 is used to classify those moving
objects into respective classes

2) Violation Detection
  The vehicles are detected using YOLOv3 model. After detecting
the vehicles, violation cases are checked Tensorflow is used for implementing the vehicle
classifier with darknet -53.
