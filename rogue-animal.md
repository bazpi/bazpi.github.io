#Rogue Animal Detection and Tracking for Pre-Crash Safety on Indian Roads

Imagine a scenario where a rogue animal is crossing a highway and cars are running at high speeds on the same track, there arises a severe possibility of an accident prone to happen, if the driver isn't paying enough attention or isn't forewarned about a possible crash by the system.

My approach to solving this problem involves the use of a Mask-RCNN Neural Network architecture for animal detection and segmentation. The video feed from a camera on a vehicle is captured by the camera is converted into images and is fed to the model. The model segments the images fed and detects where the animal is in the frame. An immediate 'Slow-Down:Animal Ahead' signal is issued when the animal is detected.

The path of the animal is predicted and notifications to slow down are issued to the driver. Inputs from other sensors, like RADAR/LIDAR/ultrasonic sensors are taken (when the animal is in range of the sensors) to estimate the approximate distance of the car from the animal and speed reduction or increase signals are issued, based on the distance and estimated path of the animal .

In addition to tracking single or herds of animals, this model can easily be extended to detect other artifacts like people, cars, trucks, trees, etc. to prevent accidents. 
