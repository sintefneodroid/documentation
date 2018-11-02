
===========================================
Approaches, hypotheses and choice of method
===========================================

The research problem in Neodroid is essentially an improved way for humans to teach robots and
for robots to learn. The motivation behind this is the often tedious development cycle involved in
robotics applications – such as illustrated in Figure 3. Here we have a farmer that wants a
strawberry-picking robot. The farmer tells the engineer about the problem, and then the engineer
tells the robot – through programming – what the problem is. Some things are usually lost in
translation, and this process repeats until the farmer is satisfied. In Neodroid, we are developing
technology that can enable a more direct transfer of knowledge from the human to the robot – via
virtual reality, as seen in Figure 4.

We are focusing on a narrow set of tasks, involving visual-motor ability. This area of research is an
area which enables robot to see and respond with a motion sequence. Existing knowledge in this
area is mature when it comes to simple tasks that can be programmatically explained – such as
putting a peg in a hole. For simple task sequences, there are robots that can be quite directly taught
by a human physically moving the robot [12]. When the tasks become complex, and/or difficult to
describe in a program, there is a need for expanded knowledge and this is where we focus –
specifically with virtual reality as the medium in which to teach robots. With that in mind, we
present the following hypotheses to be investigated in Neodroid:

In terms of methodology, we have chosen deep learning – and focus on the challenge of developing
the applicable deep learning architectures. We chose deep learning since it has the necessary tools
to handle both image processing (using convolutional neural nets [5,6]) and motion sequences
(using recurrent neural networks [13]). This is well suited to our task, in which we want a robot to
provide a motion response to a visual stimulus. Virtual reality is the primary medium we will use to
provide the example visual stimulus and end-effector motion responses. Such motion responses are
essentially the 6 DOF motion of two grippers, without consideration to the pose of the other robot
joints or the position in space of the robot. A humanoid robot – Aldebaran Pepper – will be used to
demonstrate transfer-learning from virtual reality to the real world. Inverse-kinematics algorithms
are needed in order to convert end-effector motion responses to actual motion of the humanoid
robot. NTNU and SINTEF already developed such algorithms [14] applicable to a moving
humanoid robot.

Given the methodology above, we will investigate our hypotheses through the following objectives:
Hypotheses
1) Robots can learn visual-motor ability in virtual reality.
2) Humans can teach robots visual-motor tasks in virtual reality.
3) Visual-motor skills, learnt by a robot in virtual reality, can be transferred to a robot in the
real world.
Primary objective
 Develop deep learning architectures for creating a reality-ready robot brain in virtual reality.
Secondary objectives
 Implement a virtual reality environment for training a virtual robot.
 Develop deep learning architectures for visual-motor tasks.
 Implement human operation of a robot in virtual reality.
 Demonstrate robot deep learning in virtual reality.
 Demonstrate transfer-learning between virtual reality and the real world.

+------------+------------+-----------+
| Header 1   | Header 2   | Header 3  |
+============+============+===========+
| body row 1 | column 2   | column 3  |
+------------+------------+-----------+
| body row 2 | Cells may span columns.|
+------------+------------+-----------+
| body row 3 | Cells may  | - Cells   |
+------------+ span rows. | - contain |
| body row 4 |            | - blocks. |
+------------+------------+-----------+
