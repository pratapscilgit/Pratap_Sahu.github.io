
# Automated Service Health Monitoring and Recovery

## 1. Project Overview

Developed a PowerShell-based solution to monitor service status across multiple virtual machines and automatically start services identified as stopped.

## 2. Objective

Reduce manual intervention in routine Windows service monitoring and recovery activities.

## 3. Scope of Automation

- Monitor services across multiple virtual machines.
- Identify stopped services.
- Start services identified as stopped.
- Support recurring operational monitoring.

## 4. Technologies Used

- PowerShell
- Windows Services
- Windows Server
- Remote administration

## 5. Implementation

The solution used PowerShell to check service status across multiple virtual machines and start services identified as stopped.

The service inventory, monitoring frequency and handling of startup failures should be documented according to the actual implementation.

## 6. Validation

- Verify connectivity to target virtual machines.
- Confirm service status before execution.
- Verify the start operation.
- Check the service status after execution.
- Record services that could not be recovered.

## 7. Operational Considerations

- Confirm service dependencies.
- Verify permissions required to manage remote services.
- Avoid automatically starting services that are intentionally stopped.
- Follow approved operational procedures.

## 8. Project Outcome

Reduced manual intervention in recurring service monitoring and recovery activities.

## 9. Source Code

Add an approved, sanitized original script or a clearly labelled demonstration implementation.
