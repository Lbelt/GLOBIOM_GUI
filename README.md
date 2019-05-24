## GLOBIOM_GUI

This repository provides a Graphical User Interface (GUI) for [GLOBIOM](http://www.globiom.org/). The master (default) branch is designed for the [FABLE version of GLOBIOM](https://iiasa.github.io/GLOBIOM_FABLE/).

## Getting Started

To make this repository work with [GLOBIOM_FABLE](https://github.com/iiasa/GLOBIOM_FABLE), clone it to a ``GUI`` directory co-located with the GLOBIOM ``Model`` directory. From the command line, this can be done as follows:
```
cd <directory where you cloned GLOBIOM_FABLE>
git clone https://github.com/iiasa/GLOBIOM_GUI GUI
```
This should yield a ``GUI`` directory adjacent to the ``Model`` directory.

The GUI requires Java 8 specifically, other Java versions are **not*& supported. If you do not have a Java 8 runtime installed on your machine, you can [download OpenJDK 8 here](https://adoptopenjdk.net/). Choose the HotSpot version for best performance.

After locating or installing Java 8 on your machine, edit ``GGIG_java_path.txt`` to point to the java executable/binary of the installation. It should be located in a ``bin`` subdirectory. Thereafter, the GUI can be started by running ``launch.bat``.

## Acknowledgements

The GLOBIOM GUI is based on [GGIG](http://www.ilr.uni-bonn.de/em/rsrch/ggig/ggig_e.htm), the Gams Graphical User Interface Generator. We are grateful for the generous assistance of Wolfgang Britz and Torbjörn Jansson.