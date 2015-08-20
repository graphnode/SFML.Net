# SFML.Net - Simple and Fast Multimedia Library for .Net

SFML is a simple, fast, cross-platform and object-oriented multimedia API. It provides access to windowing, graphics, audio and network.
It is originally written in C++.

## This is not the official .NET binding!
Please go to [SFML/SFML.Net](https://github.com/SFML/SFML.Net) to get the official .net binding.

## Authors
* Laurent Gomila - main developer (laurent@sfml-dev.org)
* Zachariah Brown - active maintainer (contact@zbrown.net)
* Diogo Gomes - the guy to blame if this fork breaks (dgomes@graphnode.com)

## Download
You can either download the source and build it (don't forget to download the CSFML files, read the Dependencies topic below)

## Running the Examples
You need to [download](http://www.sfml-dev.org/download/csfml/) ([or build](https://github.com/SFML/CSFML/)) the CSFML DLLs from and place them in the `/lib/x86` and/or `/lib/x64` depending on the architecture(s) you want to build the examples on.

Another dependency is the OpenTK library, this is required by some examples (opengl, vb and window) to run correctly.
It is not required unless you plan on running the example programs that are included.

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
To run SFML.NET executables you must have a copy of CSFML. CSFML can be compiled from
source (https://github.com/SFML/CSFML/) or downloaded from the offical release
page (http://www.sfml-dev.org/download/csfml/). Also note that since CSFML depends on
the main SFML project you also need all SFML runtime dependencies to build it.

## Contribute
**Note**: Please use this fork's issue tracker (https://github.com/graphnode/SFML.Net/issues), and not the official one, for issues related to this fork.

SFML and SFML.Net are open-source projects, and they need your help to go on growing and improving.
Don't hesitate to post suggestions or bug reports on the forum (http://en.sfml-dev.org/forums/)
or post new bugs/features requests on the task tracker (https://github.com/SFML/SFML.Net/issues/).
You can even fork the project on GitHub, maintain your own version and send us pull requests periodically to merge your work.
