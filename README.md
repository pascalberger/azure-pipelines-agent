# Visual Studio Team Services Agent

## Overview

The cross platform build and release agent for Team Services and Team Foundation Server 2015 and beyond.  This replaced the deprecated closed source windows build agent and the existing [xplat agent](https://github.com/Microsoft/vso-agent)

Supported on Windows, OSX, Ubuntu and Red Hat.  Written for the .NET Core CLR as one code base in C#.


## Status

|   | Build & Test |
|---|:-----:|
|![Win-x64](docs/res/win_med.png) **Windows x64**|[![Build & Test][win-x64-build-badge]][win-x64-build]| 
|![Win-x86](docs/res/win_med.png) **Windows x86**|[![Build & Test][win-x86-build-badge]][win-x86-build]| 
|![macOS](docs/res/apple_med.png) **macOS**|[![Build & Test][macOS-build-badge]][macOS-build]| 
|![Linux-x64](docs/res/linux_med.png) **Linux x64**|[![Build & Test][linux-x64-build-badge]][linux-x64-build]|
|![Linux-arm](docs/res/linux_med.png) **Linux ARM**|[![Build & Test][linux-arm-build-badge]][linux-arm-build]|

[win-x64-build-badge]: https://mseng.visualstudio.com/pipelinetools/_apis/build/status/VSTS.Agent.CI-Windows?branchName=master
[win-x64-build]: https://mseng.visualstudio.com/PipelineTools/_build?_a=completed&definitionId=6916

[win-x86-build-badge]: https://mseng.visualstudio.com/pipelinetools/_apis/build/status/VSTS.Agent.CI-Windows?branchName=master
[win-x86-build]: https://mseng.visualstudio.com/PipelineTools/_build?_a=completed&definitionId=7491

[macOS-build-badge]: https://mseng.visualstudio.com/pipelinetools/_apis/build/status/VSTS.Agent.CI-MacOS?branchName=master
[macOS-build]: https://mseng.visualstudio.com/PipelineTools/_build?_a=completed&definitionId=6917

[linux-x64-build-badge]: https://mseng.visualstudio.com/pipelinetools/_apis/build/status/VSTS.Agent.CI-Linux?branchName=master
[linux-x64-build]: https://mseng.visualstudio.com/PipelineTools/_build?_a=completed&definitionId=6915

[linux-arm-build-badge]: https://mseng.visualstudio.com/pipelinetools/_apis/build/status/VSTS.Agent.CI-Linux?branchName=master
[linux-arm-build]: https://mseng.visualstudio.com/PipelineTools/_build?_a=completed&definitionId=7490

## System Pre-Requisites

First, ensure you have the necessary system prequisites

![win](docs/res/win_sm.png) [Windows](docs/start/envwin.md)    

![macOS](docs/res/apple_sm.png) [macOS](docs/start/envosx.md)    

![linux](docs/res/linux_sm.png) [Linux](docs/start/envlinux.md)    

## Get the Agent

Next, download and configure the agent

![win](docs/res/win_sm.png)  [Start Windows](https://www.visualstudio.com/en-us/docs/build/admin/agents/v2-windows)  

![macOS](docs/res/apple_sm.png)  [Start macOS](https://www.visualstudio.com/en-us/docs/build/admin/agents/v2-osx)  

![linux](docs/res/linux_sm.png)  [Start Linux](https://www.visualstudio.com/en-us/docs/build/admin/agents/v2-linux)  

## Supported Usage

This agent can be used for the VSTS service and it replaces the node agent for TFS2015 On-Prem.

| Scenario | OSX/Unix | Windows | Comment |
|:-------------:|:-----:|:-----:|:-----:|
| VSTS      |  Yes  | Yes   |
| TFS2015 (onprem)   |  Yes  | No    | Windows use agent with 2015 |
| TFS2017 (onprem)   |  Yes  | Yes    |  |
| TFS2018 (onprem)   |  Yes  | Yes    |  |

## More Documentation

[Documentation Here](https://aka.ms/tfbuild)

## Troubleshooting

Troubleshooting tips are [located here](docs/troubleshooting.md)

## Contribute

For developers that want to contribute, [read here](docs/contribute.md) on how to build and test.
