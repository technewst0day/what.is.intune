# what is intune

[![what is intune](gett-stateed.png)](https://computersolve.com/what-is-intune/)

Intune is Microsoft’s cloud-based mobile device management (MDM) solution. It provides agentless management for devices and is hosted in Azure – which means it doesn’t require on-prem infrastructure nor will it need VPNs to manage devices.

## How does Intune work?

Intune is hosted in the Azure cloud and its management console can be accessed via a web browser, like Edge or Chrome. Much of the Intune functionality is policy-driven, which includes the following:

Device profiles for initial deployment and configuration
Configuration policies for devices and applications
Compliance policies that work with Azure Active Directory (Azure AD) to help vet conditional access to application and company data

Furthermore, policies and profiles can be deployed over the air to groups of devices or users based on what the administrator specifies. Also, profiles for initial device configuration and deployment can be distributed to Windows devices through Autopilot (or to Apple devices through Apple Business or School Manager).

## What OSes are covered with Intune?

* Intune can manage the following OSes:
* Windows 10 and 11
* Android 8.0+, Android Enterprise
* Apple macOS 10.15+, iPadOS 13.0+, iOS 13.0+

## Does Intune work with third-party software?

Intune is geared toward making it easy to patch Microsoft products. While there are some ways to update third-party apps, it costs time and/or money to make it happen.

Since Intune doesn't patch third-party applications natively, users often purchase add-on products from third-party providers to extend Intune capabilities to cover third-party application patching.

Also, Intune doesn’t support Linux operating systems nor does it help with Windows Server. This leaves organizations running SCCM (or another tool) to manage Windows Server and Linux, which usually means they have duplicative workflows and require on-prem infrastructure

## Do you need other software to use Intune?

To use Intune, your computers must be connected to Azure Active Directory, which is a cloud-hosted Active Directory. Historically, this has only existed on-prem. Thus, your devices must either be purely Azure AD-joined, or Hybrid Azure AD-joined (a combination of on-prem AD and Azure AD).

To use features like automatic MDM enrollment in Intune, you’ll need Azure AD Premium, which requires the purchase of an Enterprise Mobility + Security (EMS) subscription.
