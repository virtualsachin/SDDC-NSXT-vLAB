# SDDC-NSXT-VLAB
Ansible playbook to automate deployment of nested ESXi hosts and NSX-T

#### Table of Contents

1. [Description](#description)
1. [Setup - The basics of getting started with nsxt](#setup)
    * [Dependencies](#Dependencies)
    * [Edit answersfile.yml](#Edit answersfile.yml)
1. [Usage](#usage)
1. [Limitations)
1. [Development](#development)

## Description

This repository will be used to hold an Ansible Playbook to deploy and configure vCenter, nested ESXi VMs and the NSXT

## Setup

master branch is updated for vSphere 7.0.


### Dependencies

apt-get install sshpass python-pip git <br/>
pip install vim <br/>
pip install pyvmomi <br/>
https://github.com/virtualsachin/SDDC-NSXT-vLAB.git <br/>

Place the ESXi and VCSA ISOs in /root/ISOs <br/>


### Edit answersfile.yml

Edit answersfile.yml according to your infrastructure!

## Usage

ansible-playbook deploy.yml


## Limitations
Ansible => 2.7 is required <br/>
ESXi version 6.7 and above is supported <br/>
VCSA version 6.7 and above is supported <br/>

## Development
TODO: Optimising the Answerfile. 

