## DevContainer Environment - Purpose, Configuration, and Setup

In this document, I will discuss the configuration of the DevContainer I will be using for my Flutter application development.

**I would like to make a quick disclaimer:** at this moment in time, I do not have a fully working and functioning DevContainer environment due to a few issues that I have been working to overcome. I am currently working on resolving these issues as quickly as possible. Resultingly, for the purposes of this assignment, I will be speaking in the future tense about my DevContainer which will soon be fully functional and complete.

## :diamond_shape_with_a_dot_inside: Purpose and Benefits of the Dev Container
A DevContainer, short for Development Container, is a Docker container that is specifically designed to create development environments for software products. DevContainers have numerous qualities and features that make them extremely beneficial to the software developer and have caused them to become increasingly popular. The following are a few relevant benefits of Devcontainers:
- A significant feature of DevContainers is their ability to ensure a consistent development environment.
- DevContainers allow users to isolate dependencies and tools within them, which can later be accessed through any IDE of the user's choice.

DevContainers are extremely beneficial in the context of **Flutter application development** for the following reasons:
- The code in DevContainers will run the same way on any computer no matter what operating system the computer uses. This allows users to not have to worry about compatibility constraints that usually surface due to using different environments.
- DevContainers are extremely portable. Users can move their dev containers from one computer to computer and enjoy the comfort of working on their project on multiple computers.

## :diamond_shape_with_a_dot_inside: Configuration of the DevContainer
To configure my DevContainer, the following steps will be taken:
1) **Setting up a base image.** I will use a Docker image to set-up my Flutter environment. The purpose of the Docker image is to build, deploy, run, update, and manage my DevContainer.
2) **Any additional tools or extensions installed in the container.** Because I am developing my DevContainer within VSCode, I will make use of the Dev installer extension within VSCode. This extension allows me to use a docker container as a full-feature developer environment.
Extension: https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers

## :diamond_shape_with_a_dot_inside: Integration with VS Code
Visual Studio Code, or VSCode, is an editor that supports the Development Container specification and files with the .json format. It is able to make use of dev container properties to access and create dev containers. 

For this project, I will be using VScode to develop my dev container. Through the use of the **Visual Studio Code Dev Containers extension**, I can use a Docker container as a full-featured development environment. 

## :diamond_shape_with_a_dot_inside: Usage
As I mentioned prior, my DevContainer is not fully functional at the current moment. However, once I have it properly working, I will update this section with proper instructions for starting my container, editing the code, running my Flutter application, and other relevant workflows that pertain to the overall usage of my container.

## :diamond_shape_with_a_dot_inside: Challenges and Solutions
- One challenge I experienced at the beginning of working on this project occurred during my initial download of Docker. Because of certain settings on the computer I was using, the installation of the platform was unsuccessful. Of course, figuring out why the computer was not allowing the platform to be downloaded was of much importance, as this was an essential first step into actually making progress on the project. To solve this problem, I searched through my computer's settings to remove or turn off anything that was blocking the download.
- Another challenge I experienced was properly understanding all of the new concepts that are included within this project. The world of containers and related concepts, such as images, Docker files, and .json files, is completely brand new to me. To overcome feeling overwhelmed with information overload, I regularly spent quality time learning about these concepts by taking advantage of the resources on Canvas. Through gradual learning and practice, I slowly but surely began to better understand the new concepts and how they all relate.

## :diamond_shape_with_a_dot_inside: Conclusion

In conclusion, DevContainers are an extremely reliable, portable, and efficient way to develop environments that can be used to create software products.
In this class, a major milestone has been setting up DevContainers so that we can successfully engage in the development of Flutter web applications.
