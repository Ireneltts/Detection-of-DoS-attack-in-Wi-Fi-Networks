# Requirements

## Introduction
IoT has become a primary target for data theft. There is a legal risk if disconnection of a user from a network occurs frequently. 
Moreover, service providers would be accountable to the financial and legal issues if they fail to provide network services. 
Such vulnerabilities are the Deauthentication attack, Beacon Flooding attack and Probe Request Flooding attack during which, on behalf of a target computer, an attacker sends spoofed frames to an Access Point (AP) essentially refusing its access to the network. 
IEEE 802.11 (Wi-Fi) contains the provision for a Deauthentication frame. It also has beacon, probe request and probe response frames which are unencrypted. 
Wi-Fi Deauthentication attack, Beacon Flooding attack and Probe Request Flooding attack are types of Denial of Service (DoS) attack. 
They target the communication between a user & a Wi-Fi Access Point (AP) by spoofing the MAC address of AP. 
The scope of this project is to design a Real-Time IoT network model to detect the Deauthentication attack, Beacon Flooding attack and Probe Request Flooding attack.

## Cost and Features
### *Cost*
Less Cost and easy to deploy
### *Features*
This model can find which AP gets the respective frames. This technique can be easily deployed on open as well as encrypted networks. 
Proposed model is implemented by using ESP8266 Wi-Fi Module. It can detect these attacks in Wireless LAN (WLANs) by displaying/extracting the victim BSSID.
WPA2 Protection

## SWOT ANALYSIS
S(STRENGTH)
•Easy to detect the attack without disturbing the users
•Users will continue the access in the network without any failure
•Reduction in operation cost 

W(WEAKNESS)
•Uses only localhost
•Cannot detect any other attacks
•Error occurs if IoT device (NodeMCU) is faulty

O(OPPORTUNITIES)
•Efficient Analysis of attack and its features

T(THREATS)
•Can be vulnerable to other form of attacks


# 4W&#39;s and 1&#39;H

## Who:


## What:



## When:



## Where:


## How:



# Detail requirements
The general functional requirements of this system are:
•Monitoring the users in the Wi-Fi network
•Detecting the duplicate frames
•Sending alerts when duplicate frames are detected

Hardware Requirements
•Power source and power control
•Sensor
•Wireless Communication

Software Requirements
• Wireshark
• Python
• Scapy-Module
• Ardunio

The general non-functional requirements of this system are:
• Power Supply to the IoT sensors
• Computation Time to find the attacker
• Connection with the NodeMCU
• Low cost
• Portable

Other requirements of this project for designing this model.
• Availability: The detective mechanism should be available on all the time as many
users in the network are using AP for the Wi-Fi connection.
• Correctness: The detector should able to reach the Wi-Fi networks for detecting the
right users in the network.
• Maintainability: The network admins and the users should maintain the correct
power supply devices and IoT sensors.
• Usability: The IoT sensors should detects fake networks that should satisfy a
maximum number
