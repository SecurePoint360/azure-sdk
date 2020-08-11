---
name: Architecture Board Review Request - Introductory Session
about: Request for introductory session on an Azure service and client library with the Architecture Board
title: 'Board Review: Introducing <client library name>'
labels: architecture, board-review
assignees: lilyjma
---

Thank you for starting the process for approval of the client library for your Azure service.  Thorough review of your client library ensures that your APIs are consistent with the guidelines and the consumers of your client library have a consistently good experience when using Azure. 

**The Architecture Board reviews [Track 2 libraries](https://azure.github.io/azure-sdk/general_introduction.html) only.** If your library does not meet this requirement, please reach out to [Architecture Board](adparch@microsoft.com) before creating the issue. 

Please reference our [review process guidelines](https://azure.github.io/azure-sdk/policies_reviewprocess.html) to understand what is being asked for in the issue template.

**Before submitting, ensure you adjust the title of the issue appropriately.**

**Note that the right material must be included before a meeting can be scheduled.** 

## Contacts and Timeline

* Service team responsible for the client library:
* Main contacts:
* Expected GA date for this library:

## About the Service 

* Link to documentation introducing/describing the service:
* Link to the service REST APIs: 
* Is the goal to release a Public Preview, Private Preview, or GA? 


## About the client library

* Name of client library:
* Link to library reference documentation:
* Is there an existing SDK library? If yes, provide link: 


## Champion Scenarios (Option 1)

Please read through the Champion Scenario section [here](https://azure.github.io/azure-sdk/policies_reviewprocess.html) to understand what is considered a “Champion Scenario”

* Champion scenario 1
    * Link to library’s sample folder: 
* Champion scenario 2
    * Link to library’s sample folder:
* …
* Champion scenario n
    * Link to library’s sample folder:

## How-To Guides (Option 2)
Samples demonstrating common how-tos: 

* Create a new resource
* Read the resource
* Modify the resource
* Delete the resource
* Authentication
* Error handling 
* Handling race conditions/concurrency issues


Considering the following questions would help guide some the of library design decisions, because ultimately the library should be easy to use for common scenarios that developers want:

1. What is the app the developer is building that uses your client library?
2. Who is the end-user of the application (the developer's customer)
3. What features of the API need to be explained in the sample so that someone could use this API in a real app?


## Thank you for your submission!
    