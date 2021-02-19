# learning_yangsuite

[Get started with YANG Suite](https://developer.cisco.com/yangsuite/)

YANG Suite allows you to download data models from a network device. 

This gives you the ability to view meta data about each YANG data model to understand what is exposed within the model

In YANG Suite you are able to build an api call and send the call from within the suite.

NOTE: [YANG Explorer](https://github.com/CiscoDevNet/yang-explorer) is free and open source. 

- YANG Suite falls under the [Cisco End-User Licensing Agreement](https://www.cisco.com/c/en/us/about/legal/cloud-and-software/end_user_license_agreement.html)

- YANG Suite only supports netconf

## How to install YANG Suite

You are able to run YANG Suite as a local host

### To install using `Python`

```bash
pip install yangsuite
```

### To install as a Docker Container

1. Clone repo [here](https://github.com/CiscoDevNet/yangsuite/)

2. Generate the certificates for the HTTPS secure connection 

```bash
cd yangsuite/docker/ ; ./gen_test_certs.sh
```

3. Run docker-compose 

```docker
docker-compose up
```

4. Access the tool at https://localhost

5. Accept EULA

## Device Setup

Once YANG Suite is up and running 

To connect your devices and download their supported YANG models:

1. Go to `Setup/Create new device` to add your device to YANG Suite

2. Click `Check selected device's reachability` to ensure connectivity

3. After this is verified go to `Setup/YANG files and repositories` then click `New repository`

> Once the repo has been created all of device data models will be downloaded via `Netconf`

## Explore YANG Models

Here is where you explorer your devices YANG models

Use this to build your `Operations`

1. Click `Explore` and the select your device from `Select a YANG set`

2. Next in `Select YANG model(s)` search for the desired YANG Model

3. Once selected click `Load models`

4. Now expand the YANG Data Model to see the leafs, contains and lists that describe your data models.

## 



## Resources

[YANG Suite on GitHub](https://github.com/CiscoDevNet/yangsuite/)

[Cisco DevNet Snack Minute](https://youtu.be/3zmNDfn8b38)

## YANG Suite Setup



## About me

Introverted Network Automation Engineer that is changing lives as a Developer Advocate for Cisco DevNet. Pythons scripts are delicious. Especially at 2am on a Saturday night. 

My hangouts: 

- [LinkedIn](https://www.linkedin.com/in/duanlightfoot/) 

- [Twitter](https://twitter.com/labeveryday)
