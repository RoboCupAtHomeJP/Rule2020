# General Purpose Service Robot
In the task, robots are evaluated the skills which are required on overall Stage 1.

## NOTICE
The rule will be based on "[\[5.2. GeneralPurposeServiceRobot\] in RoboCup2018 Rulebook](https://athome.robocup.org/wp-content/uploads/2018/10/2018_rulebook.pdf)" of RoboCup2018. Please read the Rule Book for the detail.

# Additional Rules
There are some original additional rules for the Japan Open as follows.

## Command Generation
- Team leader chooses the command category.
- A TC generates a command by the command generator.
- If the robot can't understand the command, the team can choose the options below:
    - Give the command again by a TC or a custom operator.
    - Use the Continue Rule.
- You can change to the custom operator at any time.
- Each command is allowed to give to the robot three times.
- The pre-defined questions are not used.

## Retrieving the command
- A robot has to repeat the command. But it must not be parroty. The repeating must include all of the information about the command.

## Command Generator
In this competition, we will use the command generator which was used in RoboCup 2018 Montreal. You can find it [here](https://github.com/RoboCupAtHome/Montreal2018).
Note: The object name, object name, place name, and person name will be changed for this competition.

## Restart
Not allowed.

## Data Recording
Data recording is not required.

## OC Instructions
**Setup day**
- Specify and announce the locations name.
- Specify and announce the entrance and exit door.
- Announce the objects.
- Specify and announce the location where the robot has to wait for the commands.

# Score Sheet
- The maximum time for this test is 10 minutes.
- TC will consider the partial scores of each command.

|Action　　　　　　　　　　　　　　　|Score　　　|
|:-|-:|
|||
|***Getting instructions:***||
|    Understanding the command on the 1st attempt                    |3x12|
|    Understanding the command on the 1st attempt (Custom Operator)    |3x6|
|    Understanding the command at a later attempt                    |3x1|
|***First Command Successfully Solved:***||
|    Command Category 1                |12|
|    Command Category 2                |24|
|    Command Category 3                |36|
|***Second Command Successfully Solved:***||
|    Command Category 1                |24|
|    Command Category 2                |48|
|    Command Category 3                |72|
|***Third Command Successfully Solved:***||
|    Command Category 1                |48|
|    Command Category 2                |96|
|    Command Category 3                |144|
|***Leave the arena:***||
|    Leave the arena after successfully accomplishing a command    |12|
|||
|***Special penalties & bonuses:***    ||
|　Not attending                    |-50|
|　Outstanding performance        |20|
|||
|Total score (excluding penalties and bonuses)   |300|