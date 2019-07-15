# SAP S/4HANA Cloud SDK - SAP CodeJam template
## Description

**This sample repository is meant to be used only during SAP CodeJam events with a live instructor.**

This repository contains the structure and definition of a project with an application and mock servlet to create an application using the SAP S/4HANA Cloud SDK. This is the skeleton of an application that will be enhanced by participants during the SAP CodeJam.

If you are not attending an SAP CodeJam you can either [request one for free](https://www.sap.com/community/events/codejam.html#To_request_a_CodeJam_please_send_us_an_) or [check these tutorials](https://developers.sap.com/topics/s4hana-cloud-sdk.html#tutorials)

##Requirements
Participants will need an [account on GitHub](https://github.com/join) and to be [registered for the SAP Cloud Platform trial](https://developers.sap.com/tutorials/hcp-create-trial-account.html).

All other technical requirements, including an endpoint to an SAP S/4HANA system and an instance of SAP HANA with XS Advanced, will be provided during the SAP CodeJam by the live instructor.

## Download and Installation
Instructions will be provided by the live instructor during the SAP CodeJam. They can be summarized as:

1.  Fork the repository into GitHub
2.  In SAP Web IDE, right-click on the workspace and choose `Git - > Clone Repository`.
3.  Enter the URL for the forked repository. Wait until a message on the top right corner shows the clone has been successful.
3.  Right-click on the cloned project and choose `Settings`. Configure the Space (found under `Cloud Foundry` in SAP Web IDE Full Stack) to the space in which you want to deploy the application. _For example, in SAP HANA, express edition, the default space is `development`._

Configuration and extension of the application will be done as part of the exercises in the SAP CodeJam.

## License
Copyright (c) 2018 SAP SE or an SAP affiliate company. All rights reserved.
This file is licensed under the SAP Sample Code License except as noted otherwise in the [LICENSE file](https://github.com/SAP/cloud-s4-sdk-codejam/blob/master/LICENSE).

# My own notes during the CodeJam
## Links
1: Getting Started with SAP HANA, express edition and XS Advanced Applications
https://codelabs.developers.google.com/codelabs/cloud-sap-xsa-launcher

2: Setup Your S/4HANA Extensions Development Environment
https://codelabs.developers.google.com/codelabs/cloud-sap-hana-s4sdk-dev

3: Complete integration with the SAP S/4HANA system using the SAP S/4HANA Cloud SDK
https://codelabs.developers.google.com/codelabs/cloud-sap-hana-s4sdk

4: Set up Google Kubernetes Engine for a CI/CD Pipeline for S/4HANA SDKB
https://codelabs.developers.google.com/codelabs/cloud-sap-hana-s4sdk-k8

5: Add Machine Learning Functionality to Your S/4HANA SDK Application
https://codelabs.developers.google.com/codelabs/cloud-sap-hana-s4sdk-ml

## Misc info
- SYSTEM to perform database administration tasks
- XSA_DEV to log in to SAP Web IDE for SAP HANA as a developer
- XSA_ADMIN to perform administration tasks in for Extended Application Services, advanced model (XS Advanced) platform
- GCP VM external IP: 104.155.159.78
- Jenkins password BAgBodOgxw