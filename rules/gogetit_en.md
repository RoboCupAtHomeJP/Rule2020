**We are discussing about this rule now. There is a possibility this rule will change.**

# Go Get It in Unknown Envrionment
In this task, it is assumed that a robot acquires the knowledge about domestic environments through interaction with its owner when the robot is newly introduced. In particular, it is focused on object's names and their locations and we evaluate ability of acquisition and generalization about those knowledge through HRI(human-robot interaction).   

## NOTICE

**We are discussing about this rule now. There is a possibility this rule will change.**

## Focus
1. Efficient knowledge acquisition with HRI
2. Generalization of acquired knowledge
3. Mobile manipulation
4. Online mapping 

## Task
1. **Traning Phase** 
    * After the door opened, the robot and a team member (teacher) enter the arena.  

    * The teacher teaches features, names, locations and so on of three unknown objects. The teacher can use any methods for teaching that do not conflict with the rules of RoboCup@Home. Therefore, the following methods are not allowed.  
		
        - Input from external devices such as keyboard, mouse, touchpad, laptop pc and smart phone.  

    * After the teaching, the robot moves to the designated position and the team member declares the end of training phase.  

3. **Test Phase**
    Following procedure is repeated three times: 
    
    * The referee generates a sentence "Bring me \*. " to have the robot bring an object. The generated sentence includes words (e.g. object's categories, visual features, object's locations) to identify the object in the environment. Words used in the sentence is not opened. Examples of the sentences are as follows:  

		- "Bring me a juice near the standing person. "
		- "Bring me a red object in front of the TV. "

      The time taken to generate the sentence is not included in the time limit.  
 
	* A team member (instructor) instructs the robot using the sentence "Bring me \*. "  

	* If the robot cannot recognize it correctly or the instructor makes speech error, the instructor can instruct the robot three times in total. The instructor also can skip the instruction and, in this case, this instruction is considered as failure.   

	* The robot can ask if it is OK to execute the task using yes-no question. To answer the question, the instructor can only use "yes" or "no." Moreover, the instructor cannot answer "yes" to the question whose answer should be "no" and vice versa.  

	* The robot grasps the specified object, return to the designated position and hand it to the instructor.  

	* If the robot brings a false object, it is put to the original position again.   

## Additional Rules and Remarks
* **Restart:** The team can restart the task only once. In this task, time limit of restart described in the general rules is not applied. The task finish when the robot cannot restart within the time limit of the task. When the team declare the restart, the objects and their locations are changed.  

* **Room and designated position:** The room used in this task and designated position where the robot takes order are announced the previous day.  

* **Object locations:** There are objects that are not used in the environment. After the training phase, the objects are randomly moved about 10 cm.   

* **Furniture location:** The furniture's locations are changed about 30 minutes before the task. After the change, the team members cannot enter the room. 

* **Voice recognition:**  If the robot recognizes the instruction by voice, your team gets the right of bonus points. Bonus points will only be awarded if scored in each Test Phase.

* **Recognition by QR code:** When bypassing voice recognition using a QR code etc., the team member (instructor) converts the given instruction command on the device brought with your team and presents it. The OC members do not prepare QR code etc.

* **Publish the method:**  If the team publish the method with used in this task a paper or web page, your team gets the right of bonus points. The team send url of the paper or the web page to the exective comittee via e-mail the previous day. The OC will review it on the condition that the source code and ReadMe that explains how to solve the task is published. Bonus points will only be awarded if scored in this task. E-mail adress : athomejapan_ec@googlegroups.com

## Score Sheet

The maximum time for this task is 10 minutes. 

|Action　　　　　　　　　　　　　　　|Score　　　|
|:---------------------------------------|-:|
|||
|***Test Phase:***||
|　Move to the correct position			|3x40|
|　Grasp the correct object			|3x30|
|　Deliver the correct object			|3x30|
|||
|***Special penaltie & bonuses:***	||
|　Not attending					|-50|
|　Outstanding performance			|15|
|　Voice recognition				|3x10|
|　Publish the method				|35|
|||
|Total(without penalties & bonus)   |300|
