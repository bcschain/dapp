# dapp
NEO: A distributed network for the Smart Economy

NEO uses digital identity and blockchain technology to digitize assets and leverages smart contracts for autonomously managed digital assets to create a "smart economy" within a decentralized network.

To learn more about NEO, please read the White Paper|白皮书.

Supported Platforms
We already support the following platforms:

CentOS 7
Docker
macOS 10 +
We will support the following platforms in the future:


Red Hat Enterprise Linux 7.0 +
Ubuntu 14.04, Ubuntu 14.10, Ubuntu 15.04, Ubuntu 15.10, Ubuntu 16.04, Ubuntu 16.10
Windows 7 SP1 +, Windows Server 2008 R2 +

Debian
Fedora
FreeBSD
Linux Mint
OpenSUSE
Oracle Linux
Development
To start building peer applications for NEO on Windows, you need to download Visual Studio 2017 and install the .NET Core SDK.

If you need to develop on Linux or macOS, just install the .NET Core SDK.

To install Neo SDK to your project, run the following command in the Package Manager Console:

PM> Install-Package Neo
For more information about how to build DAPPs for NEO, please read the documentation|文档.

How to Contribute
You can contribute to NEO with issues and PRs. Simply filing issues for problems you encounter is a great way to contribute. Contributing implementations is greatly appreciated.

We use and recommend the following workflow:

Create an issue for your work.
You can skip this step for trivial changes.
Reuse an existing issue on the topic, if there is one.
Clearly state that you are going to take on implementing it, if that's the case. You can request that the issue be assigned to you. Note: The issue filer and the implementer don't have to be the same person.
Create a personal fork of the repository on GitHub (if you don't already have one).
Create a branch off of master(git checkout -b mybranch).
Name the branch so that it clearly communicates your intentions, such as issue-123 or githubhandle-issue.
Branches are useful since they isolate your changes from incoming changes from upstream. They also enable you to create multiple PRs from the same fork.
Make and commit your changes.
Add new tests corresponding to your change, if applicable.
Build the repository with your changes.
Make sure that the builds are clean.
Make sure that the tests are all passing, including your new tests.
Create a pull request (PR) against the upstream repository's master branch.
Push your changes to your fork on GitHub.
Note: It is OK for your PR to include a large number of commits. Once your change is accepted, you will be asked to squash your commits into one or some appropriately small number of commits before your PR is merged.

License
The NEO project is licensed under the MIT license.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTYwMjA2ODUwOV19
-->