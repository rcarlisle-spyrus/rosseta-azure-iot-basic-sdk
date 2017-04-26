# SPYRUS Azure IoT Basic SDK

This repository references SPYRUS' Rosetta Azure IoT Basic SDKs. Rosetta Azure IoT SDKs enable you add hardware backed cryptography to your IoT solution for connecting and authenticating to Azure IoT Hub.

The Rosetta Azure IoT Basic SDK provides hardware certified key storage and cryptography in several convenient form factors.  The Basic SDK supports device registration with Azure IoT Hub as well as generating Shared Access Signatures (SAS) permitting authentication while avoiding sending keys or secrets over the wire/air. The secret key used for the HMAC algorithm can be maintained within the Rosetta HSM module and the operation used to generate the SAS token can be computed within the HSM for a higher level of assurance.  The examples and documentation describe how to add support for Rosetta HSM’s to the Microsoft Open Source IoT SDK found on Github with a few simple edits or patches.

## SPYRUS Rosetta Azure IoT Basic Hardware SDK

![alt text](https://developer.spyrus.com/developer/wp-content/uploads/2017/01/Rosetta-USB.jpg)
![alt text](http://developer.spyrus.com/developer/wp-content/uploads/2017/04/001_microsdhc.png)

The hardware SDK consists of SPYRUS Rosetta HSM’s, example code and documentation that will illustrate how to raise the assurance of the authentication and communication with Microsoft’s Azure IoT Hub.  The Basic Hardware SDK includes support for all SPYRUS HSM’s without having to utilize the FIPS 140-2 L3 encrypted secure channel between the embedded system and the Rosetta HSM. 

- [Rosetta IoT Developer Site](https://developer.spyrus.com)


