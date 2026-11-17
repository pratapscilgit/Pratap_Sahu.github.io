
# Azure Snapshot Cleanup Automation

## 1. Project Overview

Created a PowerShell script to identify and remove unused Azure snapshots.

## 2. Objective

Support Azure storage housekeeping and reduce unnecessary resource accumulation.

## 3. Scope of Automation

- Identify Azure snapshots.
- Review snapshot inventory.
- Identify snapshots considered unused.
- Remove selected unused snapshots.

## 4. Technologies Used

- PowerShell
- Azure PowerShell (Az)
- Azure Managed Disk Snapshots

## 5. Implementation

The solution used PowerShell to identify and remove unused Azure snapshots.

The actual criteria used to determine whether a snapshot was unused should be documented based on the original implementation.

## 6. Validation

- Retrieve the snapshot inventory.
- Verify the snapshot selection criteria.
- Confirm that selected snapshots are approved for deletion.
- Execute the cleanup operation.
- Verify the resulting resource state.

## 7. Security and Operational Considerations

- Use appropriate Azure RBAC permissions.
- Verify snapshot ownership and retention requirements.
- Protect snapshots required for backup or recovery.
- Use an approval or review process before deletion.

## 8. Project Outcome

Supported storage housekeeping and reduced unnecessary snapshot resource accumulation.

## 9. Source Code

Add an approved, sanitized original script or a clearly labelled demonstration implementation.
