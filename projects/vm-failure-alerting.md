
# Azure VM Failure Detection and Alerting

## 1. Project Overview

Developed a PowerShell-based monitoring solution to identify Azure Virtual Machines in Failed state and generate alerts for timely investigation and remediation.

## 2. Objective

Improve visibility of Azure VM failures and support timely operational response.

## 3. Scope of Automation

- Identify Azure Virtual Machines.
- Retrieve VM state information.
- Detect VMs in Failed state.
- Generate alerts for investigation.

## 4. Technologies Used

- PowerShell
- Azure PowerShell (Az)
- Azure Virtual Machines

## 5. Implementation

The solution used PowerShell to identify Azure Virtual Machines in a Failed state and generate alerts for investigation.

The actual alert delivery mechanism, monitoring interval and failure detection criteria should be documented according to the original implementation.

## 6. Validation

- Verify Azure authentication and access.
- Retrieve the intended VM inventory.
- Verify VM state information.
- Confirm that Failed-state VMs are identified.
- Verify alert generation using an approved test scenario.

## 7. Operational Considerations

- Distinguish VM provisioning state from runtime power state.
- Validate the failure classification before generating alerts.
- Avoid exposing subscription or customer information.
- Document the investigation and remediation process.

## 8. Project Outcome

Supported timely investigation and remediation of Azure VM failures through automated detection and alerting.

## 9. Source Code

Add an approved, sanitized original script or a clearly labelled demonstration implementation.
