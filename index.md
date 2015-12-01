---
layout: default
title: Home
---

# Welcome to May1601

The goal of the project is to create a standalone security device that can be
placed in an industrial network to monitor traffic, looking for
security-related deviations, and act as a low interaction honeypot.

![Diagram of device internals](/assets/block_diagram.png)

With the dependency of electricity in the modern world, defending the
functionality and integrity of electrical power plants is integral to the
preservation and protection of our daily lives. Power plants handle extremely
volatile resources on a continuous round-the-clock basis. In order to keep
these systems up and running without fault they are monitored and controlled
by numerous components on a SCADA (Supervisory Control and Data Acquisition)
network. The integrity of this network is of vital importance. Normally these
networks are almost completely isolated from the outside world. However,
should an intruder somehow gain access to this network, it is important that
IT personal be notified immediately and that the cause of the intrusion be
identified and closed as soon as possible. This is where Honeypots come in to
play. Honeypots disguise themselves as systems on the SCADA net work,
mimicking the behavior of other devices on the network while gathering
information. Ideally, attackers on the network connect to the Honeypot
unknowingly and provide information to the IT staff allowing them to
interpret the source of the attack.
