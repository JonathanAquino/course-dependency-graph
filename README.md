# course-dependency-graph
Creates a graph showing the pre-requisite dependencies between courses in a school program.

## Installation
You will need to download and install Graphviz from http://www.graphviz.org/

## Usage
Run the following Graphviz commands to generate the graph png:

    cd examples
    ccomps -x twu-mamft.dot | dot | gvpack | neato -Tpng -n2 -o twu-mamft.png

It will generate a png like this:

![TWU MAMFT graph](https://raw.githubusercontent.com/JonathanAquino/course-dependency-graph/master/examples/twu-mamft.png)

For more information on how the above command works, see http://stackoverflow.com/a/8003622/2391566