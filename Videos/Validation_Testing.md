
# Scenario-related tests

## - V-E-01
**Goal**: Check if the green color of the Chroma stage cards allows to isolate the object by eliminating the background with images taken from the robot car.

**Result**: The following video can be viewed to validate the test.

<a href="https://youtu.be/zjQyjXJ_OiE" target="_blank"> Video F2.1: Segmentación de cubo Lego sobre escenario Chroma 2</a>

## - V-E-02
**Goal**: Check the following aspects of the scenario:
1.	It has a minimum size of 120x120 cm.
2.	The robot car can make a complete turn on the stage without hitting walls.

**Result**: The following video can be viewed to validate the test.

  <a href="https://youtu.be/eELcx224uiY" target="_blank"> V-E-02: Check stage size and complete rotation of the vehicle</a>

## - V-E-03
**Goal**: Check if the final stage has uniform lighting.

**Result**: The following video can be viewed to validate the test.

  <a href="https://youtu.be/FU5BDELNgb8" target="_blank"> V-E-03: Check stage lighting  </a>

# Tests related to the robot car

## - V-CR-01
**Goal**: Check the maximum weight the robot car can carry with its gripper system.

**Result**: The following video can be viewed to validate the test.

  <a href="https://youtu.be/Yh7WY9Arkcw" target="_blank"> V-CR-01: Maximum weight picked up by the robotic vehicle  </a>

## - V-CR-02
**Goal**: Check the operation of the sensor for approaching objects to be picked up.   

**Result**: The following video can be viewed to validate the test.

  <a href="https://youtu.be/K4eX7jM7Ry4" target="_blank"> V-CR-02: Operation of the object approach system </a>

## - V-CR-03
**Goal**: Check the size of the objects that can be picked up by the robot car's gripper system.

**Result**: The following video can be viewed to validate the test.

  <a href="https://youtu.be/l2M4URIk_jE" target="_blank"> V-CR-03: Pick up object size 6x6x4,5 cm  </a>

## - V-CR-05
**Goal**: Check the operation of the system to avoid obstacles.

**Result**: The following video can be viewed to validate the test.

  <a href="https://youtu.be/ARBE6XoJooE" target="_blank"> V-CR-05: Operation of the obstacle avoidance system </a>

## - V-CR-07
**Goal**: Check the system for detection and approach of the vehicle to the parking base.

**Result**: The following video can be viewed up to minute 2:00 to validate the test.

  <a href="https://youtu.be/KFsChXSeRE8?t=120" target="_blank"> Video F5.6: Third complete system test  </a>


# Tests related to the object detection system

## - V-SDO-01
**Goal**: Check the operation of the automatic system to collect images. These images are used as a training set for the object detection system.

**Result**: The following two videos can be viewed to validate the test.

  <a href="https://youtu.be/xBhjrggt7Lo" target="_blank"> Video F5.1: Automatic system for capturing images on Chroma stage </a>

  <a href="https://youtu.be/9aOTlK2f8YA" target="_blank"> Video F5.1 Extra: Segmentation of Lego cube images on Chroma stage in automatic system.</a>


## - V-SDO-02
**Goal**: Test the operation of the object detection system with an orange Lego cube used to train the system. This test verifies:
1.	The Lego cube segmentation task.
2.	The task of positioning in the image of Lego cubes based on their segmentation.

**Result**: The following video can be viewed up to minute 0:35 to validate the test.

  <a href="https://youtu.be/8UoTrjzoNNE" target="_blank"> Video F5.4: First full system test </a>

## - V-SDO-03 y V-SDO-04
**Goal**: Test the operation of the object detection system with Lego cubes of another color (other than orange) not used during system training. This test verifies:
1.	The segmentation task with Lego cubes of a different color than the original (orange).
2.	The task of positioning in the image of Lego cubes based on their segmentation.
3.	Data Augmentation techniques applied to generalize the detection of objects in other colors. 

**Result**: The following video can be viewed between minutes 1:13 - 1:25 to validate the test.

  <a href="https://youtu.be/ti0INz-PXlc?t=73" target="_blank"> Video F4.3: Testing of the straight-line object search and retrieval system </a>
  

## - V-SDO-05
**Goal**: Check if the object detection system rejects objects other than the one indicated (Lego cube), but with the same color (orange) of the object used in the system training.

**Result**: The following video can be viewed between minutes 0:56 - 1:12 to validate the test.

  <a href="https://youtu.be/ti0INz-PXlc?t=56" target="_blank"> Video F4.3: Testing of the straight-line object search and retrieval system </a>



