# SFML.Net - Simple and Fast Multimedia Library for .Net

[![NuGet Version](https://img.shields.io/nuget/v/Graphnode.SFML.Net.svg)](https://www.nuget.org/packages/Graphnode.SFML.Net)

**ATTENTION: The official 2.5 version of SFML.Net has been released. Please use that one.**

SFML is a simple, fast, cross-platform and object-oriented multimedia API. It provides access to windowing, graphics, audio and network.
It is originally written in C++.

## This is not the official .NET binding!
Please go to [SFML/SFML.Net](https://github.com/SFML/SFML.Net) to get the official .net binding.

**ATTENTION: The official 2.5 version of SFML.Net has been released. Please use that one.**

## Authors
* Laurent Gomila - main developer (laurent@sfml-dev.org)
* Zachariah Brown - active maintainer (contact@zbrown.net)
* Diogo Gomes - the guy to blame if this fork breaks (dgomes@graphnode.com)

## Using the Library
The easy way, and what most people want, is to use the [nuget package](https://www.nuget.org/packages/Graphnode.SFML.Net) so use IDE package manager to get it.
See the next part on how to build the source.

## Building the Source
Run the Graphnode.SFML.Net.Build project to build the source.  
It will download the CSFML dependencies automatically and create the nuget package.  
* The bin folder contains the sfml.net assemblies.
* The build folder contains the nuget package ready to go.
* The obj folder should contain the downloaded csfml files.

## Running the Examples
Open the solution and start the project in the Examples folders.  
It should do everything automatically including downloading the csfml and required nuget packages (opentk).

## Building the Documentation
You need to download the [Sandcastle Help File Builder (SHFB)](https://github.com/EWSoftware/SHFB) and then either use the Visual Studio plugin or standalone application to build the shfb project in the `/doc` directory.

## Learn
There is no tutorial for SFML.Net, but since it's a binding you can use the C++ resources:
* The official tutorials (http://www.sfml-dev.org/tutorials/)
* The online API documentation (http://www.sfml-dev.org/documentation/)
* The community wiki (https://github.com/SFML/SFML/wiki/)
* The community forum (http://en.sfml-dev.org/forums/) (or http://fr.sfml-dev.org/forums/ for French people)

Of course, you can also find the SFML.Net API documentation in the SDK.

## Dependencies
* SFML.Net requires the [CSFML](https://github.com/SFML/CSFML/) files which are automatically downloaded if they are not found.  
* OpenTK is only required in some examples for demonstrative purposes.

## Contribute
**Note**: Please use this fork's issue tracker (https://github.com/graphnode/SFML.Net/issues), and not the official one, for issues related to this fork.

**ATTENTION: The official 2.5 version of SFML.Net has been released. Please use that one.**

SFML and SFML.Net are open-source projects, and they need your help to go on growing and improving.
Don't hesitate to post suggestions or bug reports on the forum (http://en.sfml-dev.org/forums/)
or post new bugs/features requests on the task tracker (https://github.com/SFML/SFML.Net/issues/).
You can even fork the project on GitHub, maintain your own version and send us pull requests periodically to merge your work.
