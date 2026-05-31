My home lab was started as a way to headlessly host certain services 24/7 and has slowly evolved into a combination of that and a way to learn Linux and various networking fundamentals.

It consists of two primary parts:
A Raspberry Pi 5 with 16GB of RAM
A Lenovo M75q Tiny Gen 2 with a Ryzen 5 and 16GB of RAM

The Raspberry Pi functions as an edge node: all incoming traffic is routed through the Pi first. It acts as a reverse proxy (more on that in the Pi document).
The M75q is a compute node: it is the strongest part of the home lab processor-wise and thus handles the most intensive tasks (running a server, running a website, etc.)
So far for expansion, the plan is to add at least one or two more compute nodes, either in the form of other Mini PCs or perhaps old hardware of mine. This could also mean adding more storage or other upgrades to already existing hardware.