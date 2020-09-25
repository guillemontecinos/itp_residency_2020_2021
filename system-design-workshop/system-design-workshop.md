# Designing a concept based system. A practical workshop
*by Guillermo Montecinos*

## Introduction
This workshop addresses the most impoartant skills used to design a system that brings to reality an artistic concept. During the workshop we will analyze the piece [**The Revolt of Replicas**](https://guillemontecinos.cl/portfolio/the-revolt-of-replicas/) created by the workshop author as his thesis project.

## Starting from a concept

## Drafting and testing the concept 

## Designing the system

### Understanding the world as boxes and lines: Block diagrams
Every system, whatever actions it performs, can be understood as a box whose behavior inside is unknown, that takes an `input` and uses it to generate an `output`. This is the simplest system we can have.

<p align="center">
  <img src="https://github.com/guillemontecinos/itp_residency_2020_2021/blob/master/system-design-workshop/assets/basic-system.jpg" align="middle" width="40%">
</p>

Let's take, for example, [Shannon's model of communication (1948)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6773024&tag=1) which simplifies the process of communication between and emissor and a receiver to a series of boxes and lines that describe a flow of information. The `Information Source` –let's say you– emmits a message which is sent over the communication channelby the `Transmitter` –let's say your phone. The `Transmitter` receives the `Message` as an `input` and process' it in order to convert it into a `Signal`. Then, the `Signal` gets into the communication chanel (the box in the center) which also receives the noise comming from the `Noise Source`. Subsequently, the `Receiver` takes the `Received Signal` which is the `Signal` after being affected by the noise in the communication channel, and converts it into a `Message` that is received by the receiver at the `Destination`.

<p align="center">
  <img src="https://github.com/guillemontecinos/itp_residency_2020_2021/blob/master/system-design-workshop/assets/shannon-communication.jpg" align="middle" width="80%">
</p>

As you see, with a simple array of boxes and lines we can ilustrate a logical flow of data where an `input` is affected by a `System` and then converted into an `output`. Diagrams can go crazier as more complex is each system, and also can take different topographies, but let's stick with theis basic idea of boxes connected by arrows.

<p align="center">
  <img src="https://nabilaheruputri.files.wordpress.com/2014/04/g11-block-diagram.jpg" align="middle" width="80%">
</p>

### Identifying inputs and outputs

### Identifying processing units

### Sketching the system's workflow (understanding the system as a set of boxes and wires)

## Choosing tools

### Choosing tools for the processing unit

### Choosing communication protocols that connect those units

## Starting to build (how to approach it)

## Conclusion

<p align="center">
  <img src="https://github.com/guillemontecinos/itp_residency_2020_2021/blob/master/system-design-workshop/assets/system-diagram.jpg" align="middle" width="80%">
</p>

## Reference
* [Inside your computer – Ted Talk](https://www.youtube.com/watch?v=AkFi90lZmXA)
* [On Teaching the Simplification of Block Diagrams](https://www.ijee.ie/articles/Vol18-6/IJEE1332.pdf)
* [A Mathematical Theory of Communication](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6773024)
* [G11 Electronics – Early Philips Colour TV](https://philipstv.co.uk/g11-electronics/)