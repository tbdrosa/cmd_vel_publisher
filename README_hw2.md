

# README.md

**1.**  Initialize a  `.git`  repository in the package folder (ie.  `catkin_ws/src/cmd_vel_publisher/`). Add your github repository as a remote. Add the changes, commit with the message  `init`, and push the package to your github repository.

**2.**  Write a node  `infinity_node.py`  that makes the robot drive in an infinity path. Model the path as two conjoined  **perfect**  circles (radius of 2m) like the track shown below. The point of conjuction (where it crosses from one circle to the next) must be the same for the clockwise and anticlockwise crossings.

![enter image description here](https://camo.githubusercontent.com/49ba0994f26e0475fffb4ca3ae0345f6ed32f623/68747470733a2f2f70726576696577732e31323372662e636f6d2f696d616765732f686f62626974666f6f742f686f62626974666f6f74313730342f686f62626974666f6f743137303430303535332f37363335363635332d747261636b2d726f61642d696e66696e6974792d726f61642d766563746f722d686967687761792d766563746f722d696c6c757374726174696f6e2d73706565647761792d6261636b67726f756e642d2e6a7067)

**3.** Add, commit and push after completing `infinity_node.py`
**4.** Write a node that makes the robot drive in an uncircumscribed pentagram. Use the image below for the order in which the path is traversed. At each vertex, the robot must come to a complete stop, and rotate 36 degrees (internal angle of pentagram vertex).

![enter image description here](https://camo.githubusercontent.com/98bf46ff70db9595f0c15413bbe6c5a079a16836/687474703a2f2f6865726d65746963686572616c642e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031382f30342f436f756e7465722d436c6f636b777369652d50656e74616772616d2d456c656d656e74616c2d53796d626f6c732d4469616772616d2d333030783239342e706e67)

- Add, commit and push after completing  `pentagram.py`

**5.**  Create a separate launch file for each node:  `infinity.launch`  and  `pentagram.launch`

**6.**  Add, commit and push after completing the launch files.
