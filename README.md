# Yinet: A distributed ecosystem

*read in other language: [简体中文](zh/README.md)*

## Table of Contents

- [Overview](#Overview)
- [Project Design](#project-design)
  - [Paper and Documents](#paper-and-documents)
  - [Whitepaper](#whitepaper)
    - [The brief of decenteralized network](#The-brief-of-decenteralized-network)
    - [Definitions](#Definitions)
    - [Technical framework](#Technical-framework)
  - [Sub-project](#Sub-project)
- [State of project](#state-of-project)
- [License](#License)


## Overview

<p align="center">
    <img src="img/yinet.png">
</p>

## Project Design

To learn more design detail for this project, please read [Paper and Documents](#paper-and-documents). `Yinet` is made up by some sub-project for different usage.

### Paper and Documents

- [Whitepaper](#Whitepaper): Describe ` Yinet`'s aims and design principle.
  
- [RFCs](rfcs/README.md): Describe the detail of project.

### Whitepaper

#### The brief of decenteralized network

With the development of Internet technology, the mode of interactive has been
moved from the computer to the mobile phone. Nowadays, it gradually can apply
to all devices in daily life: washing machines, cameras, air conditioners, TVs,
sweeping robots, vending machines and so on.

Commercial companies have discovered these opportunities. So, they bend
themselves to speed up the production and sales of these devices. In order to
ensure these devices work properly, they spend a lot of money to build a
centralized network to manipulate every device and data. 

Centralized networks are not good at managing these exponentially large numbers
of devices. The communication, storage, and computing resources consumed by
each device may overwhelm the last straw of the centralized network. In order
to fill these cost gaps, commercial companies have to increase their production
and sales efforts. then, take the market they have captured, tell a tantalizing
story to the capitalists. If it works, they can use the money back to fill this
vicious circle in the centralized network.

There are other problems with centralized networks:

- Users do not have the power to control data;
- Lots of resources of network are wasted; 
- Production efficiency is low; 
- Products are not focused enough; and so on.
  

In this situation , surrounded by various commercial routines, users like fools.
Their privacy may be violated, resources may be idle, or even plundered. These
problems are not easy to solve, but they do exist.

Is it possible to improve this situation? There are some ideas:
    
- Design a new, distributed Internet structure;
- Try to pass part of the decentralized ideas to each device;
- Use the decentralized architecture to complete the system data flow;
- Complete the entire product process with decentralized community communication production;
- Making the whole network self-sufficient in a distributed structure.
  

Based on the above ideas, the Yinet project was designed. This is a huge project.
We hope more like-minded friends, will join us to build this new decentralized
Internet infrastructure.

#### Definitions

Yinet made some definitions of the new Internet structure, as follows:

- **Connected device**: In Yinet's structural design, the device does not exist independently, it
will maintain a certain degree of connectivity with other devices in the network.
- **Centralize all resources of devices**:  In the hands of ordinary users,
mobile phones, computers, and many other smart devices have a lot of idle
computing and storage resources. These device resources can actually be managed
more effectively. In the network designed by Yinet, resources such as storage
and computing power are not locked to a single device, but form a network that
can jointly schedule resources among all devices. The resources that each device
can use are not limited by its own performance, but only related to its authority
of this network.
- **All devices act synchronously**: The status between different devices can
be managed synchronously. For a simple example, suppose a user watches a movie
on computer. Suddenly, a phone call comes in. At this time, the phone will
suspend other work and let the user concentrate on the call. The computer
should also query the status of the phone and automatically pause the movie.
- **Effective interaction among devices**: Users can control, operate, and
interact with devices more diversely. As long as the device is online, you
can operate and write files stored on the computer at home even if you
are sitting in the office.
- **Compatible with kinds of network environments**: Device communication should ignore module restrictions and be compatible with various network environments. The connection of different devices will not be restricted to the same network environment.
- **Relative independence of device functions**: On the basis that the device can effectively establish a connection relationship, Yinet split the definition of the device.
- **Basic device**: This kind of device is responsible for providing storage, computing and other resources to the network, acting as a communication base station, and dominating the interaction of various devices in the network.
- **Functional device**: This kind of device has stable functionality and practicability, which can provide convenience to people's daily life. Most of them are the Internet-based transformation products of traditional electronic equipment or common goods.
- **Trendy device**: This type of device has a certain degree of fashion, which brings users an excellent interactive experience. It is the entrance to the network and a terminal for displaying information.
- **Other expandable devices**: Yinet is an open network that can extend access to other types of devices.
- **Unified management of user resources**: As users and consumers of the network, people should not be trapped in a centralized black box. In the Yinet architecture, users are reserved a great ability to manage device resources and their own data.
- **Users command their own devices**: Users can perform multi-level identity authentication on the devices they own, group all devices together, and form a small network that can autonomously dispatch resources. We call this small net as Personal Yinet. Users can uniformly use and manage the storage and computing power resources provided by these devices.
- **Strictly protected datazone**: After the device forms this small network, a part of the storage space becomes a personal datazone. The data generated by users in various network activities,  will be collected and organized into this datazone, and a high-level cryptography scheme is configured to ensure the security of these data. When a user accesses an application that needs to retrieve data on the device, the data pool will authorize it with certain data retrieval permissions based on different application ratings.
- **The intelligence of Yinet**: Yinet users have acquired the ability to manage device resources and their own data, which often makes the user's operations extremely complicated. In order to avoid this situation, Yinet has designed a complete intelligent infrastructure and provides a good AI assistant to complete these tasks. Users only need to give their own requirements, and enjoy themselves. The computing and storage resources required by the AI assistant will be provided by Personal Yinet.
- **Open collaboration**: Yinet will establish an open production model of Internet product , and organically integrate R & D and engineering.

#### Background

#### Technical framework

We present the graph of all modules in `Yinet`.

> Graph here.

Please read rfc:[0001-architecture-of-yinet.md](text/0001-architecture-of-yinet.md)

### Sub-project

- [Stem](https://github.com/Yinet-project/Stem): A distributed infrastructure.
- [Lightcore](https://github.com/Yinet-project/Lightcore): A lightweight flexible
blockchain framework.
- [Hodor](https://github.com/Yinet-project/Hodor): Distributed AI Helper with RDF.
- [Karma](https://github.com/Yinet-project/Karma): Advance cryptography toolkits.
- [Vida](https://github.com/Yinet-project/Stem): Misc project of `Yinet` for application.
- [Curdata](#): Application at financial.

## State of project

***Yinet is a work in process!***

We present project's roadmap here.

### Contribute

There are many way to contribute us. We welcome all type of contributions.

#### Help with the design

Please create issue for related project to discuss. Then you can propose a RFC
to make these discuss to be a standard.

#### Help with the implementations

You can make issue and pull request for related implementation project.

## License

LGPL-3.0
