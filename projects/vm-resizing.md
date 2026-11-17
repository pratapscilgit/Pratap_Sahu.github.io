
# Azure Virtual Machine Resizing Automation

## 1. Project Overview

Developed a PowerShell script to resize Azure Virtual Machines using a predefined list of VM names.

## 2. Objective

Improve accuracy and reduce configuration errors during Azure VM resizing operations.

## 3. Scope of Automation

- Process predefined VM names.
- Retrieve existing VM SKU information.
- Validate current VM configurations.
- Execute VM resizing operations.

## 4. Technologies Used

- PowerShell
- Azure PowerShell (Az)
- Azure Virtual Machines

## 5. Implementation

The solution used a predefined list of VM names and included validation of existing VM SKUs before executing resizing operations.

The target VM SKU selection and operational approval process should be documented according to the actual implementation.

## 6. Validation

- Verify that the intended VM is selected.
- Verify the existing VM SKU.
- Confirm the requested resize operation.
- Retrieve the VM configuration after execution.
- Verify that the expected VM size is applied.

## 7. Operational Considerations

- Check VM resize compatibility.
- Review availability of the target VM size.
- Consider application downtime and maintenance windows.
- Follow appropriate change approval procedures.

## 8. Project Outcome

Improved accuracy and reduced configuration errors in recurring Azure VM resizing activities.

## 9. Source Code

Add an approved, sanitized original script or a clearly labelled demonstration implementation.
