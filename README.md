# LSEMgmt365

**LSEMgmt365** is a PowerShell module for managing and monitoring Microsoft 365 environments, including tasks like user activity tracking, license usage, group management, and mailbox usage monitoring.

## Features
- `Connect-CloudServices`: Establish a connection to Microsoft 365 services.
- `Get-M365UserActivity`: Retrieve activity logs for Microsoft 365 users.
- `Get-M365LicenseUsage`: Retrieve Microsoft 365 license usage.
- `New-M365Group`: Create a new Microsoft 365 group.
- `Get-M365SecurityComplianceStatus`: Retrieve security and compliance status of your Microsoft 365 environment.
- `Monitor-M365MailboxUsage`: Track mailbox usage in Microsoft 365.

## Installation

To install this module from the PowerShell Gallery:

```PowerShell
Install-Module -Name LSEMgmt365 -Repository PSGallery
```

## Usage
Here are some usage examples:

#### Connect to Microsoft 365 services
```PowerShell
Connect-CloudServices -Service "M365"
```

#### Get Microsoft 365 user activity logs
```PowerShell
Get-M365UserActivity -UserName "user@example.com" -Type "Email"
```

#### Monitor Microsoft 365 license usage
```PowerShell
Get-M365LicenseUsage
```
