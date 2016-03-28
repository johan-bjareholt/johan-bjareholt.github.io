---
layout: post
title:  "Homebrain"
date:   2015-10-05 12:00:00
status: In Development
categories: project keyboards
---
Status: In Development

Homebrain is a project aiming to make your home IoT devices work together under one protocol to one central server (the homebrain).
The project currently consists of the Homebrain server, a collection of agents for homebrain server to control IoT devices, and homebrain clients that can control homebrain.

Homebrain is a server with a message passing system and a collection of agents.
The message passing system is flexible and allows all agents to talk to eachother.
The agents are the components that makes homebrain do things.
They are often a service that can control some IoT device such as a lamp handler or a temperature sensor logger,
but can also be listeners that passes messages from the IoT devices to the homebrain message system, such as a REST listener, udp broadcast listener or websocket server.
There is also a web interface where you can configure homebrain as well as see the status of the homebrain agents and your IoT devices.

The current homebrain clients are a android app as well as a Speech-To-Text client that allows you to controll homebrain with your voice.

Homebrain is open source and the project can be found on [GitHub](https://github.com/Homebrain).
