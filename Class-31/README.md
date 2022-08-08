# Class-31
## I’ve reviewed the following topic:

- Docker


A container is a kind of virtualization. We are likely all familiar with virtual machines (VMs) in which we take one physical computer, and make many virtual computers by running a hypervisor. Hypervisors are a kind of operating system that work by presenting “virtual hardware” to a virtual machine and controlling the physical resources of the computer between multiple virtual machines.

Similarly, a container virtualized part of the computer, only instead of the whole computer like a virtual machine, containers virtualize applications.

So you have an operating system, like Linux or Windows, that’s running, and that operating system controls access to resources like memory, CPU, files, and provides services like link libraries and APIs and all kinds of software functions. And you have many applications, programs, running doing all sorts of things. Applications can crash and have access to various parts of the computer, so we virtualize them, land we call those virtualized applications “containers”.

To virtualize them, we run a program like Docker, which manages all those containers. It presents copies of things like system files and manages resources to each container, as well as allowing Systems Administrators to manage those containers. There are other versions of container systems, like LXCs and Jails, and while they differ in details, they’re fundamentally the same thing - application virtualization systems.

There are lots of advantages to running containers - application state management, isolation, security, and stability - and a few disadvantages, but they’re becoming popular.

Virtualization is about abstraction, and containers are just another layer of abstraction.





