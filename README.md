## Project Summary

This repository belongs to the [Sub1-Ghz-RF-Data-TX-RX](https://github.com/marcfarssac/Sub1-Ghz-RF-Data-TX-RX) project as explained below. Refer to the Readme file of that one to know about the project. Read below to know about this repository.

This project contains settings to disable the standard debug features in TI-RTOS projects for the CC1310 SimpleLink Sub-1 GHz Ultra-Low Power Wireless Microcontroller. It has been used in the "IoT temperature sensors" project from Marc Farssac using the following configuration.

### Project configuration summary

It uses two CC1330 M3 Cortex ARM Microcontrollers from Texas Instruments, one working as a sender and the other as a reciever. Temperature readings are being simulated using a varistor.

![20181217_112639](https://user-images.githubusercontent.com/18221570/50081476-dd68fc00-01ee-11e9-98d0-7ad239eadab6.jpg)

## Project Usage

This project shall be imported to the workspace of the other Texas Instruments projects in [Marc Farssac](https://github.com/marcfarssac) GitHub account. It can be used for other TI projects as well. 

It is used when creating "production" releases for the TI-RTOS without debug features.  Import this project to the workspace. Rename it to "tirtos_builds_CC1310_LAUNCHXL_release_ccs" if needed.

The Kernel section of the TI-RTOS [SimpleLink MCU SDK User's Guide](http://dev.ti.com/tirex/content/simplelink_cc13x0_sdk_1_40_00_10/docs/simplelink_mcu_sdk/Users_Guide.html) provides additional details on how applications use this project.

| Properties       | Configuration settings                    |
|-----------|-----------|
|<img src="https://user-images.githubusercontent.com/18221570/50077239-24052900-01e4-11e9-84eb-af896c08952b.PNG" width=500></img> | <img src="https://user-images.githubusercontent.com/18221570/50077240-249dbf80-01e4-11e9-9b01-3f39bdf312d1.PNG" width=500></img>|


## License
Copyright 2018 Marc Farssac

Licensed to the Apache Software Foundation (ASF) under one or more contributor license agreements. See the NOTICE file distributed with this work for additional information regarding copyright ownership. The ASF licenses this file to you under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

