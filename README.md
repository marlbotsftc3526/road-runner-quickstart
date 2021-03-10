# fork of acmerobotics/road-runner


## connecting to robot

connect laptop to robot wifi (FTC-nlx)

terminal:

  adb connect 192.168.43.1:5555

  adb devices


"REV Robotics Control Hub" should appear in Android Studio device dropdown list

If Android Studio build fails due to dependencies, connect to internet, rebuild,
and then reconnect to robot to install.



## Road Runner Quickstart

An example FTC project using [Road Runner](https://github.com/acmerobotics/road-runner). **Note:** Road Runner is in alpha and many of its APIs are incubating.

## Installation

For more detailed instructions on getting Road Runner setup in your own project, see the [Road Runner README](https://github.com/acmerobotics/road-runner#core).

1. Download or clone this repo with `git clone https://github.com/acmerobotics/road-runner-quickstart`.

1. Open the project in Android Studio and build `TeamCode` like any other `ftc_app` project.

1. If you have trouble with multidex, enable proguard by changing `useProguard` to `true` in `build.common.gradle`.

## Documentation

Check out the new [online quickstart documentation](https://acme-robotics.gitbook.io/road-runner/quickstart/introduction).
