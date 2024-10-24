# Azure Pipelines Tasks

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

![Tasks](/taskbanner.png "Tasks")

## Overview
This repo contains the tasks that are provided out-of-the-box with Azure Pipelines and Team Foundation Server.

This provides open examples on how we write tasks which will help you write other tasks which can be uploaded to your account or server.  See **Writing Tasks** below.

## Status
|   | Build & Test |
|---|:-----:|
|![Win](docs/res/win_med.png) **Windows**|[![Build & Test][win-build-badge]][win-build]| 
|![macOS](docs/res/apple_med.png) **macOS**|[![Build & Test][macOS-build-badge]][macOS-build]| 
|![Linux](docs/res/linux_med.png) **Linux**|[![Build & Test][linux-build-badge]][linux-build]|

[win-build-badge]: https://dev.azure.com/mseng/PipelineTools/_apis/build/status/azure-pipelines-tasks.ci-windows
[win-build]: https://dev.azure.com/mseng/PipelineTools/_build/latest?definitionId=7634

[macOS-build-badge]: https://dev.azure.com/mseng/PipelineTools/_apis/build/status/azure-pipelines-tasks.ci-macos
[macOS-build]: https://dev.azure.com/mseng/PipelineTools/_build/latest?definitionId=7635

[linux-build-badge]: https://dev.azure.com/mseng/PipelineTools/_apis/build/status/azure-pipelines-tasks.ci-linux
[linux-build]: https://dev.azure.com/mseng/PipelineTools/_build/latest?definitionId=7636

## How to Use Tasks

See the documentation for [Continuous integration and deployment](https://aka.ms/tfbuild).

## Writing Tasks

If you need custom functionality in your build/release, it is usually simpler to use the existing script running tasks such as the PowerShell or Bash tasks.  Writing a new task may be appropriate if you need deeper integration or reusability in many build definitions

Tasks are simply tool runners.  They know how to run MSBuild, VSTest, etc... in a first class way and handle return codes, how to treat std/err out, and how to write timeline records based on expected output.  They also get access to credentials to write back to TFS/Azure Pipelines. 

For uploading custom tasks to Azure Pipelines use the [TFS Cross Platform Command Line utility](https://github.com/Microsoft/tfs-cli).

Tasks can also be deployed with an Azure DevOps extension. See [this tutorial](https://docs.microsoft.com/en-us/vsts/extend/develop/add-build-task) for how to write a custom task and package it inside an extension.

## Contributing

This project welcomes [contributions and suggestions](docs/contribute.md).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟 