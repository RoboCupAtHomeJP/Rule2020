# Robot Inspection
"Robot Inspection" is adapted as one of the tasks in world competition, which is to inspect the safeness.
In the task, robots will be tested for minimal performance of basic function (eg. open the door, navigation, etc.)
and safety measurements (eg. collision avoidance, emergency stop, etc.).
Teams can get scores from this.

<!--"Robot Inspection" which is a safety test about the robot on the world competition is adopted as one of the tasks.-->
<!--In this task, robots are tested safety.-->
<!--In the task, robots will be tested about minimal performance to attend competition, and safety.-->
<!--Teams can get a score in the task.-->



## NOTICE
<!--A rule ob the task will be based on "[\[4.4 Robot Inspection\] in RoboCup2018 Rulebook](https://athome.robocup.org/-wp-content/uploads/2018/10/2018_rulebook.pdf)" of RoboCup2018.-->
<!--**We are discussing about this rule now. There is a possibility this rule will change.**-->
Please check the [video](https://youtu.be/JweIZ0n_2gs). This video introduces the inspection task.

## Focus
1. Detect Door Opening
2. Navigation
3. Avoid Person
4. Emergency Stop Button

## Task
### 1. Detect Door Opening
The robot has to wait at the entrance of the arena until the start of the task.
At that time, the door is closed.
Once TC opens the door, task begins.
The robot has to detect the open of door, and enter the arena autonomously.
<!--
タスクが開始されるまで，ロボットはアリーナの入り口で待機する．
この時，アリーナの入り口に設置されているドアは閉じている．
タスクが開始されると，TCによりドアが開かれる．
ロボットはドアが開かれたことを検出して，自律的にアリーナへ入場する．
-->

### 2. Navigation
The robot moves to the exit of the arena automatically.
<!--アリーナへ入場したロボットは，自動的にアリーナの出口に向かわなければならない．-->

### 3. Avoid Person
While the robot is moving, TC will block the robot's path.
When the robot detects TC, it has to avoid TC safely or stop until TC leaves.
<!--
ロボットの移動中，TCはロボットの進路を妨害する．
ロボットはTCを検知して，TCを安全に避けるか，TCが去るまでその場に停止しなければならない．
-->

### 4. Emergency Stop
While the robot is moving, TC will push the emergency stop button.
At that time, the robot has to stop safely and immediately.
<!--
ロボットの移動中，TCはロボットに備え付けられたEmergency stop buttonを押す．
ロボットはEmergency stop buttonを押されると，安全かつ速やかにその場で停止しなければならない．
-->


## Additional Rules and Remarks
* Skip "Detect Door Opening":
The team can skip "Detect Door Opening" part.
If your team want to skip the part, please tell TC before starting the task.
In addition, the team has to prepare a starting method of the robot (ex, touch the arm, push the button), and inform TC about it.
The "starting method of the robot" has to be an action by TC.
If the team selects the skipping "Detect Door Opening" part, the score of "Detect door opening and enter the arena" will be 0.
<!--
* Detect Door Openingのスキップ：
Detect Door Openingはスキップすることが可能である．
スキップする場合は，タスク開始前にTCにその旨を伝えること．
また「アームに触れる」「ボタンを押す」など，別途ロボットの起動方法を用意し，その起動方法をTCに伝えること．
起動方法はTCによる1動作で完了すること．
なお，Detect Door Openingをスキップすると「ドアオープンを検出し，アリーナへ入場した」のスコアは0となる．
-->

* Skip "Avoid Person":
The team can skip "Avoid person" part.
If your team want to skip the part, please tell TC before starting the task.
If the team selects the skipping of "Avoid person" part,
the score of "Avoid TC / stop on the spot without contacting the TC." will be 0.
<!--
* Avoid Personのスキップ：
Avoid Personはスキップすることが可能である．
スキップする場合は，タスク開始前にTCにその旨を伝えること．
なお，Avoid Personをスキップすると「TCに接触することなく，TCを避けた／その場で停止した」のスコアは0となる．
-->

* Score: 
In this task, only one highest score is recorded as the score of the task.
<!--
* スコア：
このタスクでは，最高得点のみがスコアとして記録される．
-->

* Number of trials: 
The task doesn't have a limit of trial.
The team can try the task again and again until the team achieves a perfect score while the time of "Robot Inspection".
<!--
* 試行回数：
このタスクの試行回数に制限はない．Robot Inspectionとして指定されている時間の許す限り，満点を達成するまで何度でも挑戦することができる．
-->

* Multiple Robots: 
If your team want to use multiple robots in the competition, all robots must attend to "Robot Inspection".
In addition, if your team want to change the sensor, actuator, or other electric equipment for other tasks,
all modification of the robot must pass the to "Robot Inspection".
<!--
* 複数台のロボット：
競技に参加するロボットが複数台居る場合，全てのロボットがRobot Inspectionに参加すること．
また，競技毎にロボットに搭載されるセンサやアクチュエータが変更される場合，競技で使用される全てのバージョンでRobot Inspectionに参加すること．
なおこれらの場合でも，チームのスコアとして全ロボットの全バージョンによる全ての試行の中から最高点のみが選ばれ，採用される．
-->

* Emergency Stop Button：
All robots must have "Emergency stop button".
(see [RoboCup 2018 Rule Book 3.4.4. & 3.8.1.](https://athome.robocup.org/wp-content/uploads/2018/10/2018_rulebook.pdf))
If the robot doesn't have an emergency stop button, the robot will be disqualified.
<!--「Emergency stop button」は，ロボットに必須の要件である．-->
<!--（[RoboCup 2018 Rule Book 3.4.4. & 3.8.1.](https://athome.robocup.org/wp-content/uploads/2018/10/2018_rulebook.pdf)参照．）-->
<!--これがないロボットは失格となる．-->



## Score Sheet
The time limit is 5 minutes.
<!--1回の制限時間は5分である．-->

|Action　　　　　　　　　　　　　　　|Score　　　|
|:---------------------------------------|-:|
|||
|***Pick and Place:***||
|　Detect door opening and enter the arena                        |20|
|　Automatically start to move to arena exit                      |20|
|　Avoid TC / stop on the spot without contacting the TC	        |30|
|　Safety and immediately stop once "Emergency stop button" is pushed  |30|
|||
|***Special penalties:***	||
|　Not attending				                                          |-50|
|||
|Total score (excluding penalties)                                |100|


