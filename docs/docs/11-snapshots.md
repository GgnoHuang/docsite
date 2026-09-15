---
id: snapshots
sidebar_position: 11
---

# Snapshot Function

On the **Snapshots** page, you can manage all created snapshots. The snapshot and restore features simplify your project's workflow. Below is an introduction and operation guide for these features:

---

## **Notice of Snapshot and Image Billing Policy Update**

To provide users with a more flexible and efficient way to manage environments and data, the platform will update the quota and billing mechanism for Snapshot and Image services effective December 1, 2026, at 00:00 (UTC+8).
After the update, Storage package quotas will apply exclusively to Datadrive storage. Snapshot and Image resources will no longer consume Storage quotas and will instead be billed based on their actual storage usage with hourly billing.
The updated billing rules are as follows:
- Billing rate: 0.0139 credits/hour
- Billing starts once a Snapshot or Image is successfully created
- Billing stops once the corresponding Snapshot or Image is deleted
This adjustment is designed to provide greater flexibility in resource management and allow users to optimize costs based on actual usage.

If you have any questions, please contact us here: [Click here to contact us](/docs/19-contact-us.md)


## Two Tabs on the **Snapshots** Page:

- **Available**: The list of all available snapshots that you can view and manage.
- **Restorable**: The list of deleted snapshots that can still be restored within a certain period.

### **Snapshot List Fields**

- **ID**: The unique identifier of the snapshot.
- **Name**: The snapshot name, making it easy for users to identify.
- **Size**: The storage space occupied by the snapshot.
- **Status**: The current status of the snapshot (e.g., Available).
- **Create Time**: The creation time of the snapshot.
- **Action**: The executable operations (detailed below).

### **Action Buttons**

- **Edit**: Modify the name of the snapshot.
- **Delete**:
  - In **Available**, deleting a snapshot will move it to the **Restorable** tab.
  - In **Restorable**, deleting a snapshot will permanently remove it, and it cannot be restored.

![Snapshots list](../docs-images/p08/01.Snapshots%20list.jpg)

## **Notes**

1. **Deletion and Restoration**:

   - After deleting a snapshot, it will move to the **Restorable** tab, where you can choose to restore or permanently delete it.

2. **Name Modification**:

   - You can modify the snapshot name at any time for easier management and identification.

3. **Storage Management**:
   - Regularly cleaning up unnecessary snapshots can free up storage space and ensure effective resource utilization.

With these features, you can easily manage and protect your data, ensuring you can quickly restore to a specific state when needed.
