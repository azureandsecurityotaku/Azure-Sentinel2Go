# Microsoft Sentinel To-Go!

[![Open_Threat_Research Community](https://img.shields.io/badge/Open_Threat_Research-Community-brightgreen.svg)](https://twitter.com/OTR_Community)
[![Open Source Love](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

<img src="resources/images/logo.png" alt="Microsoft Sentinel To-Go!" width="650"/>

Microsoft Sentinel To-Go is an open source project developed to expedite the deployment of a Microsoft Sentinel lab along with other resources for research purposes. It also comes with the option to ingest pre-recorded datasets from the [Security Datasets](https://securitydatasets.com/) project right at deployment time.

## Grocery List - Deployment Options

A few deployments available through Microsoft Sentinel To-go!

| Items | Deploy | Deploy US Gov |
| :---| :---| :--- |
| [Microsoft Sentinel](https://github.com/OTRF/Microsoft-Sentinel2Go/tree/master/microsoft-sentinel) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fmicrosoft-sentinel%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fmicrosoft-sentinel%2Fuidefinition.json) | [![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fmicrosoft-sentinel%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fmicrosoft-sentinel%2Fuidefinition.json) |
| [Microsoft Sentinel + Custom Log Pipeline](https://github.com/OTRF/Microsoft-Sentinel2Go/tree/master/grocery-list/custom-log-pipeline) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2Fcustom-log-pipeline%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2Fcustom-log-pipeline%2Fuidefinition.json) | [![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2Fcustom-log-pipeline%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2Fcustom-log-pipeline%2Fuidefinition.json) |
| [Microsoft Sentinel + Win10 Workstations](https://github.com/OTRF/Microsoft-Sentinel2Go/tree/master/grocery-list/Win10) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10%2Fuidefinition.json) | [![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10%2Fuidefinition.json) |
| [Microsoft Sentinel + Win10 + AD](https://github.com/OTRF/Microsoft-Sentinel2Go/tree/master/grocery-list/Win10-AD) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD%2Fuidefinition.json) | [![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD%2Fuidefinition.json) |
| [Microsoft Sentinel + Win10 + AD + WEC](https://github.com/OTRF/Microsoft-Sentinel2Go/tree/master/grocery-list/Win10-AD-WEC) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD-WEC%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD-WEC%2Fuidefinition.json) | [![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD-WEC%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD-WEC%2Fuidefinition.json) |
| [Microsoft Sentinel + Win10 + RPC Firewall](https://github.com/OTRF/Microsoft-Sentinel2Go/tree/master/grocery-list/Win10-RPCFW) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-RPCFW%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-RPCFW%2Fuidefinition.json) | [![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-RPCFW%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-RPCFW%2Fuidefinition.json) |
| [Microsoft Sentinel + Win10 + AD + ADFS](https://github.com/OTRF/Microsoft-Sentinel2Go/tree/master/grocery-list/Win10-AD-ADFS) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD-ADFS%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD-ADFS%2Fuidefinition.json) | [![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD-ADFS%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD-ADFS%2Fuidefinition.json) |
| [Microsoft Sentinel + Win10 + AD + MXS](https://github.com/OTRF/Microsoft-Sentinel2Go/tree/master/grocery-list/Win10-AD-MXS) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD-MXS%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD-MXS%2Fuidefinition.json) | [![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD-MXS%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-AD-MXS%2Fuidefinition.json) |
| [Microsoft Sentinel + Win10 + Palo Alto Networks VM-Series Firewall](https://github.com/OTRF/Microsoft-Sentinel2Go/tree/master/grocery-list/Win10-PAN-FW) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-PAN-FW%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-PAN-FW%2Fuidefinition.json) | [![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-PAN-FW%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FWin10-PAN-FW%2Fuidefinition.json) |
| [Microsoft Sentinel + Linux (Ubuntu,CentOS,RHEL)](https://github.com/OTRF/Microsoft-Sentinel2Go/tree/master/grocery-list/Linux) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FLinux%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FLinux%2Fuidefinition.json) | [![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FLinux%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FLinux%2Fuidefinition.json) |
| [Microsoft Sentinel + CEF Server (Ubuntu)](https://github.com/OTRF/Microsoft-Sentinel2Go/tree/master/grocery-list/CEF-Log-Analytics-Agent) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FCEF-Log-Analytics-Agent%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FCEF-Log-Analytics-Agent%2Fuidefinition.json) | [![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FCEF-Log-Analytics-Agent%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FOTRF%2FMicrosoft-Sentinel2Go%2Fmaster%2Fgrocery-list%2FCEF-Log-Analytics-Agent%2Fuidefinition.json) |

## Media

* [Microsoft Sentinel To-Go (Part 1): A lab w/ Prerecorded Data 😈 & a Custom Logs Pipe via ARM Templates 🚀](https://techcommunity.microsoft.com/t5/azure-sentinel/azure-sentinel-to-go-sentinel-lab-w-prerecorded-data-amp-a/ba-p/1260191)
* [Microsoft Sentinel To-Go (Part 2): Integrating a Basic Windows Lab 🧪 via ARM Templates 🚀](https://techcommunity.microsoft.com/t5/azure-sentinel/azure-sentinel-to-go-part2-integrating-a-basic-windows-lab-via/ba-p/1742165)
* [Testing the New Version of the Windows Security Events Connector with Microsoft Sentinel To-Go!](https://techcommunity.microsoft.com/t5/azure-sentinel/testing-the-new-version-of-the-windows-security-events-connector/ba-p/2483369)
* [Microsoft Sentinel To-Go! A Linux 🐧 Lab with AUOMS Set Up to Learn About the OMI Vulnerability 💥](https://techcommunity.microsoft.com/t5/azure-sentinel/azure-sentinel-to-go-a-linux-lab-with-auoms-set-up-to-learn/ba-p/2772581)

## Maintainers

* Roberto Rodriguez ([@Cyb3rWard0g](https://twitter.com/Cyb3rWard0g))

## Committers
