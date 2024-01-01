# Honeynet-in-Azure

## Description
The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.

The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and plot it on an Azure Sentinel Map!

## Languages Used
PowerShell: Extract RDP failed logon logs from Windows Event Viewer
https://github.com/ravana-one/Honeynet-in-Azure/issues/1#issuecomment-1873523136

## Utilities Used
ipgeolocation.io: IP Address to Geolocation API
https://github.com/ravana-one/Honeynet-in-Azure/issues/1#issuecomment-1873522396
