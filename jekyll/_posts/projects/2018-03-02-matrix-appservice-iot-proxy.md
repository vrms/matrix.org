---
layout: project
title: matrix-appservice-iot-proxy
categories: projects other
description: A proxy for the client/server API to make IoT virtual devices easier
author: Travis Ralston
maturity: Beta
language: 
license: 
repo: 
---

# {{ page.title }}
Heavily inspired by the work done by Intents in the matrix-appservice-bridge JS library, matrix-appservice-iot-proxy is a server-side application which ensures that virtual users are created and joined to the applicable rooms for each request.

This makes your IoT device code as simple as posting to a room without having to worry about the user being registered by the appservice or even being in the room. This is fully intended to have some sort of appservice powering a fleet of IoT devices such that each device is part of a given namespace.

The source (and more information) can be found on [GitHub](https://github.com/turt2live/matrix-appservice-iot-proxy).
