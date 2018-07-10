---
layout: layout.pug
navigationTitle:  Release Notes
title: Release Notes
menuWeight: 130
excerpt: Release Notes for version 0.1.0-2.3.1
featureMaturity:
enterprise: false
---
## Version 2.3.1

This is the first release of Prometheus to Universe. Based on the latest stable release version of Prometheus, version 2.3.1, this installation would be supported on DCOS cluster 1.10 and above. This has been built using current stable version of SDK (Version 0.42.1).

### Breaking Changes
This is a first release and you must perform a fresh install . 

### Features
Based on the latest stable release of the dcos-commons SDK (Version 0.42.1), this installation provides numerous benefits: 
   - Integration with DC/OS features such as virtual networking and integration with DC/OS access controls.
   - Orchestrated software and configuration update, 
   - Ability to add new nodes
   - Increase memory and CPU
   - Installation on DCOS Cluster provides the ability to restart and replace nodes.
   - Placement constraints for pods.
   - Graceful shutdown for nodes
   - Foldered Installation
   - Highly Available Prometheus server
   - Highly Available Alert Manger
   - Federation Support for Prometheus
   - Firing alerts to Alert Manager
   - Notification to third party apps like slack via Alert Manager
   - Auto discovery of cluster agent nodes
   - Service discovery
   - multiple modes of graphing and dashboarding support for grafana 
   - Support for promQL
   - Support Prometheus Expression Browser UI and Alert Manager UI via EdgeLB.

### Documentation

Released first version of Service Guide with following topics:

    - Overview
    - Install and Customize
    - Security
    - Uninstall
    - Quick Start
    - Connecting Clients
    - Managing
    - Security
    - Troubleshooting
    - API Reference
    - Command-reference
    - Connecting-clients
    - Deploy-best-practice
    - Limitations
    - Supported Versions
    - Release Notes
   
