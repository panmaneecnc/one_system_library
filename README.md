<Img src="https://github.com/deltarobotone/image_database/blob/master/logos/logos%20(6).PNG" width=500>

How to install the library? Follow this link for a short introduction using the official arduino IDE:

[**>>>install the library<<<**](https://github.com/deltarobotone/one_system_library/wiki/Install-the-library)

If you start the robot at the first time use the full system demo to check out how Delta-Robot One works.

[**>>>full system demo<<<**](https://github.com/deltarobotone/one_system_library/wiki/Full-system-demo)

The second step is to write your own applications for this robot using the system library.
Do some examples first to learn how to use the library functions works! Use the one system library wiki to check out all examples.

[**>>>one system library wiki<<<**](https://github.com/deltarobotone/one_system_library/wiki)

Examples are implemented in the one system library. If you use the arduino IDE navigate to <br>**File->Examples->OneSystemLibrary**  and check out what you can do with this smart little robot.

We recommended the move basic example to do your own first moves with the robot.

[**>>>move basic example<<<**](https://github.com/deltarobotone/one_system_library/wiki/Move-basic-example)

If you want to learn something about the workingspace of the robot check out the documentation or use the workingspace example:

[**>>>workingspace documentation<<<**](https://github.com/deltarobotone/how_to_build_your_robot/wiki/Workingspace)

You can use the demo to move around the working area of the robot.

[**>>>workingspace example<<<**](https://github.com/deltarobotone/one_system_library/wiki/Workingspace)

## API-Class
| **Class**                   | **Function/Object**              | **Example**          |
| --------------------------- | ------------------------------- | -------------------- |
| **DeltaRobotOne**           |DeltaRobotOne                    |[Hello World](https://github.com/deltarobotone/one_system_library/wiki/Hello-World)|
|                             |setup                            |[Hello World](https://github.com/deltarobotone/one_system_library/wiki/Hello-World)|
|                             |setID                            |[Remote example](https://github.com/deltarobotone/one_system_library/wiki/Remote-example)|
|                             |getID                            |ToDo|
|                             |functions                        |[Functions example](https://github.com/deltarobotone/one_system_library/wiki/Functions-example)|
|                             |move                             |[Move basic example](https://github.com/deltarobotone/one_system_library/wiki/Move-basic-example)<br>[Speed control example](https://github.com/deltarobotone/one_system_library/wiki/Speed-control-example)<br>[Kinematics example](https://github.com/deltarobotone/one_system_library/wiki/Kinematics-example)|
|                             |light                            |[Light basic example](https://github.com/deltarobotone/one_system_library/wiki/Light-basic-example)<br>[Light blink example](https://github.com/deltarobotone/one_system_library/wiki/Light-blink-example)<br>[Light fade example](https://github.com/deltarobotone/one_system_library/wiki/Light-fade-example)|
|                             |display                          |[Display example](https://github.com/deltarobotone/one_system_library/wiki/Display-example)|
|                             |button                           |[Button example](https://github.com/deltarobotone/one_system_library/wiki/Button-example)|
|                             |encoder                          |[Encoder example](https://github.com/deltarobotone/one_system_library/wiki/Encoder-example)|
|                             |power                            |[Hello World](https://github.com/deltarobotone/one_system_library/wiki/Hello-World)<br>[Remote example](https://github.com/deltarobotone/one_system_library/wiki/Remote-example)|
|                             |gripper                          |[Gripper example](https://github.com/deltarobotone/one_system_library/wiki/Gripper-example)|
|                             |remote                           |[Remote example](https://github.com/deltarobotone/one_system_library/wiki/Remote-example)|
|                             |screen                           |[Screen example](https://github.com/deltarobotone/one_system_library/wiki/Screen-example)|
|                             |menu                             |[Menu example](https://github.com/deltarobotone/one_system_library/wiki/Menu-example)|
|                             |livemode                         |ToDo|
|                             |servosetup                       |ToDo|
| ------------------------------- | ------------------------------- | ------------------------------- |

## API-Functions

| **Class**                   | **Function**                    | **Example**          |
| --------------------------- | ------------------------------- | -------------------- |
| **Button**                  |push                             |[Button example](https://github.com/deltarobotone/one_system_library/wiki/Button-example)|
|                             |release                          |[Button example](https://github.com/deltarobotone/one_system_library/wiki/Button-example)|
|                             |clicked                          |[Button example](https://github.com/deltarobotone/one_system_library/wiki/Button-example)|
|**Display**                 |printLine1                       |[Display example](https://github.com/deltarobotone/one_system_library/wiki/Display-example)|
|                             |printLine2                       |[Display example](https://github.com/deltarobotone/one_system_library/wiki/Display-example)|
|                             |printText                        |[Display example](https://github.com/deltarobotone/one_system_library/wiki/Display-example)|
|                             |printSign                        |ToDo|
|**Encoder**                  |setup                            |ToDo|
|                             |getValue                         |[Encoder example](https://github.com/deltarobotone/one_system_library/wiki/Encoder-example)|
|                             |setValue                         |ToDo|
|                             |setLimitMin                      |[Encoder example](https://github.com/deltarobotone/one_system_library/wiki/Encoder-example)|
|                             |setLimitMax                      |[Encoder example](https://github.com/deltarobotone/one_system_library/wiki/Encoder-example)|
|                             |getLimitMin                      |ToDo|
|                             |getLimitMax                      |ToDo|
|                             |reset                            |[Encoder example](https://github.com/deltarobotone/one_system_library/wiki/Encoder-example)|
|**ExternalMotor**            |start                            |[External motor example](https://github.com/deltarobotone/one_system_library/wiki/External-motor-example)|
|                             |stop                             |[External motor example](https://github.com/deltarobotone/one_system_library/wiki/External-motor-example)|
|                             |getSpeed                         |ToDo|
|                             |setSpeed                         |[External motor example](https://github.com/deltarobotone/one_system_library/wiki/External-motor-example)|
|                             |getStatus                        |ToDo|
|                             |control                          |ToDo|
|**Functions**                |waitFor                          |[Functions example](https://github.com/deltarobotone/one_system_library/wiki/Functions-example)|
|                             |pulse                            |[Encoder example](https://github.com/deltarobotone/one_system_library/wiki/Encoder-example)|
|**Gripper**                  |open                             |[Gripper example](https://github.com/deltarobotone/one_system_library/wiki/Gripper-example)|
|                             |close                            |[Gripper example](https://github.com/deltarobotone/one_system_library/wiki/Gripper-example)|
|                             |getStatus                        |[Gripper example](https://github.com/deltarobotone/one_system_library/wiki/Gripper-example)|
|**Light**                    |on                               |[Light basic example](https://github.com/deltarobotone/one_system_library/wiki/Light-basic-example)|
|                             |off                              |[Light basic example](https://github.com/deltarobotone/one_system_library/wiki/Light-basic-example)|
|                             |setColour                        |[Light basic example](https://github.com/deltarobotone/one_system_library/wiki/Light-basic-example)|
|                             |setIntensity                     |[Light basic example](https://github.com/deltarobotone/one_system_library/wiki/Light-basic-example)|
|                             |blink                            |[Light blink example](https://github.com/deltarobotone/one_system_library/wiki/Light-blink-example)|
|                             |blinkFast                        |[Light blink example](https://github.com/deltarobotone/one_system_library/wiki/Light-blink-example)|
|                             |blinkSlow                        |[Light blink example](https://github.com/deltarobotone/one_system_library/wiki/Light-blink-example)|
|                             |blinkTime                        |[Light blink example](https://github.com/deltarobotone/one_system_library/wiki/Light-blink-example)|
|                             |fade                             |[Light fade example](https://github.com/deltarobotone/one_system_library/wiki/Light-fade-example)|
|                             |fadeFast                         |[Light fade example](https://github.com/deltarobotone/one_system_library/wiki/Light-fade-example)|
|                             |fadeSlow                         |[Light fade example](https://github.com/deltarobotone/one_system_library/wiki/Light-fade-example)|
|                             |fadeReset                        |[Light fade example](https://github.com/deltarobotone/one_system_library/wiki/Light-fade-example)|
|                             |heartbeat                        |[Light fade example](https://github.com/deltarobotone/one_system_library/wiki/Light-fade-example)|
|**Menu**                     |setItem                          |[Menu example](https://github.com/deltarobotone/one_system_library/wiki/Menu-example)|
|                             |start                            |[Menu example](https://github.com/deltarobotone/one_system_library/wiki/Menu-example)|
|**Move**                     |setup                            |ToDo|
|                             |setupPosition                    |ToDo|
|                             |ptp                              |[Move basic example](https://github.com/deltarobotone/one_system_library/wiki/Move-basic-example)<br>[Speed control example](https://github.com/deltarobotone/one_system_library/wiki/Speed-control-example)|
|                             |getPosition                      |ToDo|
|                             |getAngles                        |ToDo|
|                             |setKinematics                    |[Kinematics example](https://github.com/deltarobotone/one_system_library/wiki/Kinematics-example)|
|                             |setWorkingSpace                  |[Kinematics example](https://github.com/deltarobotone/one_system_library/wiki/Kinematics-example)|
|**Power**                    |bluetoothOn                      |[Remote example](https://github.com/deltarobotone/one_system_library/wiki/Remote-example)|
|                             |bluetoothOff                     |[Remote example](https://github.com/deltarobotone/one_system_library/wiki/Remote-example)|
|                             |mainOn                           |[Hello World](https://github.com/deltarobotone/one_system_library/wiki/Hello-World)|
|                             |mainOff                          |ToDo|
|**Remote**                   |setID                            |ToDo|
|                             |control                          |[Remote example](https://github.com/deltarobotone/one_system_library/wiki/Remote-example)|
|**Screen**                   |info                             |[Screen example](https://github.com/deltarobotone/one_system_library/wiki/Screen-example)|
|                             |progress                         |[Screen example](https://github.com/deltarobotone/one_system_library/wiki/Screen-example)|
|                             |ready                            |[Screen example](https://github.com/deltarobotone/one_system_library/wiki/Screen-example)|
|                             |limit                            |[Screen example](https://github.com/deltarobotone/one_system_library/wiki/Screen-example)|
|                             |signals                          |[Screen example](https://github.com/deltarobotone/one_system_library/wiki/Screen-example)|
|                             |angles                           |[Screen example](https://github.com/deltarobotone/one_system_library/wiki/Screen-example)|
|                             |position                         |[Screen example](https://github.com/deltarobotone/one_system_library/wiki/Screen-example)|
|**ServoSetup**               |start                            |ToDo|
|**LiveMode**                 |start                            |ToDo|
| ------------------------------- | ------------------------------- | ------------------------------- |

## Data-Classes

| **Class**                   | **Data**                        | **API Class**        |
| --------------------------- | ------------------------------- | -------------------- |
|**Pos**                      |x                                |Move                  |
|                             |y                                |Move                  |
|                             |z                                |Move                  |
| ------------------------------- | ------------------------------- | ------------------------------- |

## Constants

| **Namespace**               | **Constant**                    | **API-Class**        |
| --------------------------- | ------------------------------- | -------------------- |
|**DeltaRobot**               |home                             |Move                  |
|**Colour**                   |red                              |Light                 |
|                             |green                            |Light                 |
|                             |blue                             |Light                 |
|                             |yellow                           |Light                 |
|                             |magenta                          |Light                 |
|                             |cyan                             |Light                 |
|                             |white                            |Light                 |
|**Intensity**                |off                              |Light                 |
|                             |min                              |Light                 |
|                             |half                             |Light                 |
|                             |max                              |Light                 |
|**Speed**                    |slow                             |Move                  |
|                             |half                             |Move                  |
|                             |fast                             |Move                  |
|                             |full                             |Move                  |
|**Signs**                    |arrowLeft                        |Display               |
|                             |arrowRight                       |Display               |
|                             |full                             |Display               |
| ------------------------------- | ------------------------------- | ------------------------------- |

| **Namespace**               | **Constant**                    | **Value**            |
| --------------------------- | ------------------------------- | -------------------- |
|**Pins**                     |servoA                           |10                    |
|                             |servoB                           |9                     |
|                             |servoC                           |6                     |
|                             |mainPower                        |13                    |
|                             |bluetoothPower                   |4                     |
|                             |externalMotor                    |11                    |
|                             |gripper                          |14                    |
|                             |ledR                             |7                     |
|                             |ledG                             |12                    |
|                             |ledB                             |8                     |
|                             |ledI                             |5                     |
|                             |buttonTop                        |15                    |
|                             |buttonCenter                     |17                    |
|                             |buttonEncoder                    |16                    |
|                             |encoderA                         |3                     |
|                             |encoderB                         |2                     |
| ------------------------------- | ------------------------------- | ------------------------------- |
