# Windows Sandbox Utilites

Windows Sandbox allows users to run a lightweight desktop environment in a secure Hyper-V isolated container. It creates a disposable instance of Windows that enables the ability to run any win32 application you wish with a pristine configuration every time you start it. It allows you to do virtually whatever you want within an isolated desktop environment without requiring any cleanup after the fact. Whether it be testing an unknown application or performing large computational tasks with many temporary files, Windows Sandbox makes it easy to employ a dedicated environment for whatever task is at hand.

This repository is a dedicated space for useful scripts and configuration files to be used with Windows Sandbox. It is a mixture of utilities generated by both the Microsoft kernel team and the community of Windows Sandbox users. If you want to learn more about how Windows Sandbox works please go to the MSDN documentation here https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-sandbox/windows-sandbox-overview.

## Contents

Outline the file contents of the repository. It helps users navigate the codebase, build configuration and any related assets.

| File/folder       | Description                                |
|-------------------|--------------------------------------------|
| `Folding In Sandbox`             | Run the Folding@Home Client in Windows Sandbox                        |
| `CONTRIBUTING.md` | Guidelines for contributing to this repository.|

## Prerequisites

A host computer running Windows 10 Pro or Enterprise Insider build 18362 or newer is currently needed to run Windows Sandbox. In addition to this you must ensure that virtualization is enabled on your machine:
- If you are using a physical machine, ensure virtualization capabilities are enabled in the BIOS.
- If you are using a virtual machine, enable nested virtualization with this PowerShell cmdlet:
    
    ```Set-VMProcessor -VMName <VMName> -ExposeVirtualizationExtensions $true```

## Contributing

**NOTE**: This repository is only for utilities to be used with Windows Sandbox. If you would like to submit feedback for Windows Sandbox itself, please go through our [Feedback Portal](https://aka.ms/windowssandbox-fb).

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
