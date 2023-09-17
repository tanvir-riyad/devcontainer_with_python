# devcontainer_with_python

DevContainers help solve the infamous "It works on my machine" problem in software development. This issue arises when a developer's code runs correctly on their local machine but encounters problems when deployed or
run on another developer's machine or in a different environment. DevContainers address this problem by providing an isolated and consistent development environment for all team members

# devcontainer.json:
It is a configuration file specifically used by Visual Studio Code's 'DevContainers' extension to define the development environment settings for your project.It focuses on configuring the development environment and enhancing the development experience within Visual Studio Code.

# Dockerfile
In the context of DevContainers, the Dockerfile is used to specify how the base development environment image should be customized. It includes instructions for installing additional packages, configuring system settings, or adding files to the image.


The process to open the project in the devcontainer:
    1. Install vscode and DevContainer extension   
    2. If the project has a .devconfiguration folder and devcontainer.json in it, vscode prompt you to "Reopen in Container" or press ctrl+shift+p.   
    3. vscode setup the process may take few minutes   
    4. Once the setup is complete, Visual Studio Code will open a new instance of the editor inside the DevContainer.

The provided devcontainer.json configuration instructs Visual Studio Code's devcontainers extension to create a development container, which, in turn, will create a Docker container with Ubuntu installed as the operating system. Inside this Docker container, the specified packages and settings will be installed, allowing us to develop our project within this isolated development environment. This approach ensures consistency and reproducibility across different development environments and makes it easier to manage project dependencies.
