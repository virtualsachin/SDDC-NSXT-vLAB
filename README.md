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

Install the required software on your Ansible controller:

sudo apt install python3 python3-pip xorriso git<br/>
sudo pip3 install ansible pyvim pyvmomi netaddr jmespath dnspython<br/>
ansible-galaxy collection install community.general community.vmware ansible.posix<br/>
git clone https://github.com/rutgerblom/SDDC.Lab.git<br/>


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

