---
layout: default
modal-id: 3
title: Broker Graph
subtitle: Supporting Cross-Device Resource Sharing by Encoding Relationships Between Applications
img: img/broker_preview.png
description: A conceptual framework for the discovery of digital resources in ubiquitous computing environments.
links:
    - title: Github
      icon: fa-github
      url: https://github.com/peter-hamilton/broker-graph
tags:
    - JavaScript
    - Node.js
    - React
    - Firebase
---

The Broker Graph project was the primary focus of my graduate work at the University of Toronto.
A description of the [concepts](https://github.com/peter-hamilton/broker-graph/docs/CONCEPTS.md){:target="_blank"} and [architecture](https://github.com/peter-hamilton/broker-graph/docs/ARCHITECTURE.md){:target="_blank"} can be found on the Broker-Graph GitHub page.

## Summary

There are many options for sharing digital resources (i.e., pictures, articles, etc.) between internet connected devices. The digital location (URL) of a digital resource can be saved on shared storage services (e.g., Dropbox, OneDrive), sent via a messaging application (e.g., email, SMS), transmitted using an application that harnesses a device's sensor-based capabilities (e.g., AirDrop, NFC), or communicated using a seemingly endless selection of other techniques.

While users have many resource sharing options to choose from, **choosing between sharing techniques is difficult**. There exists no one-size-fits-all approach to sharing digital resources across devices. Each technique provides a particular user experience, which may or may not be suitable for a given scenario. User's must consider constraints such as device capabilities, which applications the devices are running, which user accounts are setup and available on each device, and which "walled garden" each relevant device, application, and file inhabits.

<img class="project-img" src="img/broker_graph_formation.gif"/>

The goal of the Broker Graph is to improve sharing by helping users understand the patchwork of communication channels that exist between the devices in their environment, while minimizing added developer costs. This is achieved by creating a unified standard for flexibly describing the communication channels between applications and the resources (i.e., URLs) shared between them. The result is a graph data structure that encodes the relationships between and within software and hardware ecosystems. The Broker Graph was inspired by social networking platforms (e.g., Facebook, Twitter) that capture complex networks of social relationships and interactions in a machine-readable format. These platforms analyze users’ explicitly specified relationships (e.g., friends, follows) to curate massive amounts of digital content. Similarly, the Broker Graph encodes the communication channels between application instances and allows any internet connected application to share resources, register connections to other applications, and query the collection of resources shared by connected applications. Notably, this approach scales as the complexity of the web of digital relationships increases.
