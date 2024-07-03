## Tutorial: Getting started from scratch with Docker on Linux

*Last update: 2024.07.03*

### Foreword

At the time the bulk of this tutorial was written, the Docker stable release version was v19.03.14.  As of the latest quickstart update the version is 27.0.3.

In this tutorial you will learn how to:
    ▪ install Docker and run it, pulling images to your host platform,
    ▪ make your own Docker images and push them to DockerHub, the Docker registry, or to your own repo,
    ▪ physically copy local Docker images to transfer them on to another host,
    ▪ understand and make use of Docker’s networking capabilities.
Generally speaking this tutorial contains hands-on information and some background on the technology involved.  By following it you will gain first-hand experience on how to put Docker to basic use.  In a series of online tutorials, Docker offers a more in-depth presentation for devs to get started1 with docker swarms and orchestrated Docker clusters.

### Reporting issues
Corrections and suggestions are welcome and should be consigned in the Issues section of [this repo](https://github.com/Cbhihe/Doc_docker-quickstart/issues).

### Copyright

    Copyright (c) 2017-2022 Cedric Bhihe

You may reproduce and distribute the present document freely (as in “free beer”), provided you comply with three conditions: 

- the author's name, Cedric Bhihe, must be quoted in full, as well as his affiliation at time of creation (2017),
- the document must be distributed in full, as is, or not at all.

The above conditions complement the terms of the GNU Free Documentation License Version 1.3 or or any later version published by the Free Software Foundation. You can consult the full licensing terms either on the Free Software Foundation web site, or in the adjoined License.md file.

The authors' common affiliation at time of document's creation was: <BR>
     Dept of Architecture of Computers (DAC)<BR>
     Barcelona College of Computer Science (FIB)<BR>
     Polytechnic University of Catalonia (UPC)<BR>
     Barcelona 08034 - Spain
