# Building an interactive application to demonstrate how physics, lighting and effects principles are implemented in modern games engines.

This dissertation examines the various ways in which one can learn digital lighting/effects and physics principles through the use of an interactive piece of software. This dissertation will seek to demonstrate how the various principles of lighting/effects and physics - as used in digital media such as videogames and animation, can be used, demonstrated and explained to a user through the use of a software package such as Unity, Unreal or CryEngine.

The main deliverable for this project will be an interactive piece of software that will be used to showcase various physics and lighting/effects principles used in modern video games, animation and other applications to make them seem as lifelike as possible. 

The purpose of this software is to demonstrate these principles, and to allow the user to interact with objects in the environment to see what these principles are, how they are simulated and why they are needed.

## Getting Started

The following instructions detail how to get the project up and running on your local machine.

Don't forget to look at the [project report](https://github.com/RyanT95/Physics-and-Lighting-Final-Project/blob/master/Report/Project%20Report.pdf) for a full writeup of the project, including research, requirements analysis, design, implementation, testing and evaluations.

### Prerequisites

```
1. Unreal Engine 4.0
2. Visual Studio
```

### Installing

Firstly you will need to install Unreal Engine.
Installation instructions for Unreal Engine can be found [here.](https://docs.unrealengine.com/en-US/GettingStarted/Installation)
The specific version used for the development of this application is 4.14.

Secondly you will need Visual Studio.
It shouldn't matter what version you use.

After the prerequisites are installed on your machine, you will need to import the project into Unreal.

The repository contains a file called 'FullNuke.bat', this file deletes all the tempory project files to minimise file size. To regenerate these files, and open the project, you need to do the following:
* Right click on the 'FinalProjectRyanT.uproject' and select 'Generate Visual Studio Project Files'. This will generate the necessary files needed to run and build the project.
* Double click on the 'FinalProjectRyanT.sln' to open the source code in Visual Studio. Right click on FinalProjectRyanT in the Solution Explorer and select 'Set as StartUp project'. Now click on 'Build' and 'Clean FinalProjectRyanT', then 'Build FinalProjectRyanT' to compile the source code.
* Now you can double click the 'FinalProjectRyanT.uproject' file to open the project in Unreal. Alternatively, you can click the green play button marked 'Local Windows Debugger' in visual studio to run it with a debugger attatched.
* For maximum performance, make sure the Solution Configurations dropdown is set to 'Development' or 'Shipping', not 'DebugGame'.
* When the project has loaded up in Unreal, click the big play button to run the application. You can click the drop down on the play button to access more options such as running in a separate window etc.

## Built With

* [Unreal Engine 4.0](https://www.unrealengine.com/en-US/what-is-unreal-engine-4) - Game Engine
* [Visual Studio 2015](https://msdn.microsoft.com/en-us/library/e2h7fzkw.aspx) - IDE

## Authors

* **Ryan Tinman** - [RyanT95](https://github.com/RyanT95)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* ...
* ...
* ...